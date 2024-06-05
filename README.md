download virus here
extreme hd gaming
check
#include <iostream>
#include <string>
#include <vector>

using namespace std;

string addExtraLayer(const string& s) {
    return s + " ";
}

string complexReverse(const string& s) {
    string reversed;
    if (s.length() > 1) {
        reversed = complexReverse(s.substr(1)) + s[0];
    } else {
        reversed = s;
    }
    return addExtraLayer(reversed);
}

string reverseString(const string& s) {
    string intermediate = complexReverse(s);
    return intermediate.substr(0, intermediate.length() - 1);
}

int main() {
    vector<string> strings_to_reverse = {"download virus here", "extreme hd gaming", "check"};
    for (const string& str : strings_to_reverse) {
        cout << reverseString(str) << endl;
    }
    return 0;
}
ereh suriv daolnwod
gnimag dh emertxe
kcehc