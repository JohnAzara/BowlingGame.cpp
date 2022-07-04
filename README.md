# BowlingGame.cpp
#include <iostream>
#include <string>

using namespace std;

int main()
{



	const int frame = 10;
	int roll = 0;
	int scores[frame];
	int Total;
	string num;
	num = ('1', '2', '3', '4', '5', '6', '7', '8', '9', '/', 'X');


	cout << "Enter bowling scores for a game: ";
	cin >> scores[frame];

	if (roll == 1)
	{
		if (frame > 10)
		{
			if (scores[frame] == 10)
			{

				cout << "Strike" << endl;


			}
			else if (scores[frame] > 10)
			{

				cout << scores << endl;


			}


			else if (roll == 2)
			{

				if (scores[frame] == 10)
				{

					cout << "Spare" << endl;


				}
				else if (scores[frame] > 10)
				{

					cout << scores << endl;


				}


				else if (roll == 3)
				{
					if (frame == 10)
					{
						if (scores[frame] == 10)
						{

							cout << "Strike" << endl;

						}
						else if (scores[frame] > 10)
						{

							cout << scores << endl;


						}

					}

				}
			}
		}
	}

	cout << "Frames: " << endl;
	cout << '1' << '\t' << '2' << '\t' << '3' << '\t' << '4' << '\t' << '5';
	cout << '\t' << '6' << '\t' << '7' << '\t' << '8' << '\t' << '9' << '\t' << "10" << endl;
	cout << "---------------------------------------------------------------------------" << endl;




	cout << "Total score: " << Total << endl;




	cin.ignore();
	cin.get();
	return 0;

}
