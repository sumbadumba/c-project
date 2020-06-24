# c-project#include "stdafx.h"

void PrintVector(vector<int> &vecs)
{
	vectorTwo.push_back(i);

}


int main()
{
	vector<double> doubleVector(10);

	double max = -numeric_limits<double>::infinity();
	for (size_t i = 0; i < doubleVector.size(); i++)
	{
		cout << "Enter score " << i + 1 << ": ";
		cin >> doubleVector[i];
		if (doubleVector[i] > max)
		{
			max = doubleVector[i];
		}
	}
	max /= 100.0f;

	for (auto& element : doubleVector)
	{
		element /= max;
		cout << element << " ";
	}
	////////////////////////////////

	//가변길이

	//vector<double> doubleVector2;
	//double max2 = -numeric_limits<double>::infinity();
	//for (size_t i = 1; true; i++)
	//{
	//	double temp;
	//	cout << "Enter score " << i << "(-1 to stop): ";
	//	cin >> temp;
	//	if (temp == -1)
	//	{
	//		break;
	//	}
	//	doubleVector2.push_back(temp);
	//	if (temp > max2)
	//	{
	//		max2 = temp;
	//	}
	//}
	//max2 /= 100.0f;
	//for (auto& element : doubleVector2)
	//{
	//	element /= max2;
	//	cout << element << " ";
	//}
	//
	//vector<int> intVector;
	//vecotr<int>intVector2(10, 100);
	//for (int i = 0; i < intVector2.size(); i++)
	//{
	//	cout << intVector2[i] << endl;
	//
	//}

	//vector<int > intVector3({ 1,2,3,4,5,6 });
	//
	//for (zuto vec : intVector3)
	//	cout << vec << endl;

	vector<int> intVector(10);
	intVector.assign(5, 100);
	intVector.assign({ 1,2,3,4 });

	vector<int> vectorOne(10, 0);
	vector<int> vectorTwo(5, 100);
	vectorOne.swap(vectorTwo);

	vector<int>vectorOne(10);
	vvector<int> vectorTwo(10);

	if (vectorOne == vectorTwo)
	{
		cout << "equal!" << endl;

	}
	else
	{
		cout << "not equal" << endl;

	}
	vectorOne[3] = 50;
	if (vectorOne < vectorTwo)
	{
		cout << "vectorOne is less than vectorTwo" << endl;
	}
	else
	{
		cout << "vectorOne is not less than vetorTwo" << endl;

	}

	vector<double> doubleVector;
	double max = -numer_limits<double>::INFINITY();

	max /= 100.0f;
	for (vector<double>::iterator iter = doubleVector.begin();
		iter != doubleVector.end(); iter++)
	{
		*iter /= max;
		cout << *iter << "";

	}
	for (auto iter = begin(doubleVector);
		iter != end(doubleVector); ++iter);
	{
		*iter /= max;
	}
	vector<int>intVetor(10);
	auto it = begin(intVector);
	it += 5;
	--it;
	*it = 4;

	vector<int> vectorOne = { 1,2,3,5 };
	vector<int > vectorTwo;

	vectorOne.insert(vectorOne.cbegin()+3,4)//c++이론 , 자료구조 , 가상함수

		for (int i = 6; i <= 10; i++)
		{
			vectorTwo.puch_back(i);
	    }

	PrintVector(vectorOne);
	PrintVector(vectorTwo);
	vectorOne.insert(vectorOne.cend(), vectorTwo.cbegin());
	PrintVector(vectorOne);

	vectorOne.erase(vectiorOne.cbegin() _1, vectorOne.cbegin() + 5);
	PrintVector.clear();

	vectorTwo.insert(vectorTwo.cbegin(), 10, 100);

	vectorTwo.pop_back)back();
	PrintVector(vetorTwo);
}





	
