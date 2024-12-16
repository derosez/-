>全排列

```cpp
#include<vector>
#include<algorithm>
#include<iostream>

using namespace std;

vector<int> Initial_Nums = { 1, 2, 3 }; //定义初始数组

int main(){

	cout << "Initial_Nums: ";
	for (auto num : Initial_Nums) {
		cout << num << " ";
	}
	cout << endl;

	while (next_permutation(Initial_Nums.begin(), Initial_Nums.end())) {  //next_permutation函数
		cout << "next permutation:";
		for (auto num : Initial_Nums) {
			cout << num << " ";
		}
		cout << endl;
	}

	return 0;
}
