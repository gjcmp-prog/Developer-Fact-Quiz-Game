//5 Question io console Quiz Game :)

#include <iostream>
using namespace std;

int main()
{
    string favfootteam = "Dallas Cowboys";       //Correct answer for Favorite Football Team
    string favbasketteam = "Dallas Mavericks";  //Correct answer for Favorite Basketball Team
    string favelang = "Java";                  //Correct answer for Favorite Programming Language
    string zodSign = "Scorpio";               //Correct answer for Zodiac Sign
    string favgameconsole = "Atari";         //Correct answer for if I am a Gam


    int footteamguess;
    int basketteamguess;
    int langguess;
    int zodSignguess;
    int gameconsoleguess;

    


    cout << "\n LET'S PLAY A GAME!";
    cout << "\n\n Which of the following Professional Football Teams is my favorite ? : ";
    cout << "\n\n 1. Miami Dolphins, 2. Dallas Cowboys, or 3. Green Bay Packers?";
    cin >> footteamguess;
    if (footteamguess == 2) {
        cout << "\n Correct! Great Job!";
        cout << "\n\n Which of the following Professional Basketball Teams is my favorite ? :";
        cout << "\n\n 1. Dallas Mavericks, 2. Chicago Bulls, or 3. Brooklyn Nets?";
        cin >> basketteamguess;
        if (basketteamguess == 1) {
            cout << "\n Correct! You are killing it!";
            cout << "\n\n Which of the following Programming Languages do I like best ? :";
            cout << "\n\n 1. Python, 2. C++, or 3. Java?";
            cin >> langguess;
            if (langguess == 2) {
                cout << "\n Correct again! Hmm...are you cheating?";
                cout << "\n\n Which of these is my Zodiac Sign?:";
                cout << "\n\n 1. Libra  2. Capricorn or 3. Scorpio?";
                cin >> zodSignguess;
                if (zodSignguess == 3) {
                    cout << "\n Correct! Random Fact: 8 and 1 are lucky numbers for Scorpio this year!";
                    cout << "\n\n FINAL QUESTION";
                    cout << "\n\n What is my favorite video game console?";
                    cout << "\n\n 1. Atari 2. NES or 3. Sega Genesis?";
                    cin >> gameconsoleguess;
                    if (gameconsoleguess == 1) {
                        cout << "\n CONGRATULATIONS! You have proven your knowledge of the all powerful programmer of this game!";
                        cout << "\n\n Now, go forth and do cool things in life :)";
                    }
                    else {
                        cout << "\n Incorrect! So Close! Game Over :(";
                    }
                }
                else {
                    cout << "\n Incorrect! Game Over :(";
                }
            }
            else {
                cout << "\n Incorrect! Game Over :(";
            }
        }
        else {
            cout << "\n Incorrect! Game Over :(";
        }
    }
    
    else {
        cout << "\n Incorrect! Game Over :(";
    }





    system("pause>0"); //omits garbage text from bottom of Console


    return 0;

}
