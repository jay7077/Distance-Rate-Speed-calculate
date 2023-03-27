#include<iostream>
#include<math.h>

using namespace std;

int main()
{
    //Time Calculate
    
    double distance;
    double speed;
    double time;
    
    cout << "Enter the Distance traveled in kilometer: ";
    cin >> distance;
    
    cout << "Enter the speed: ";
    cin >> speed;
    
    time = distance / speed;
    
    cout << "The time taken is " << time << " hours" << endl;
    
    // Speed Calculate
    
    
    cout << "Enter the distance traveled: ";
    cin >> distance;
    
    cout << "Enter the time taken: ";
    cin >> time;
    
    speed = distance / time;
    
    cout << "The speed is " << speed << " kph" << endl;
    
    // Distance calculate
    
    
    cout << "Enter the time taken: ";
    cin >> time;
    
    cout << "Enter the speed: ";
    cin >> time;
    
    distance = time * speed;
    
    cout << "The distance traveled is: " << distance << " kilometer" << endl;
    
    return 0;
}

