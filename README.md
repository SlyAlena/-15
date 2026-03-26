# Z15

Уровень 1

Задание 1

    #include<iostream>
    using namespace std;

    int main() {
	setlocale(LC_ALL, "Russian");
	int n;
	cin >> n;
	switch (n) {
		case 1: cout << "Стой"; break;
		case 2: cout << "Готовься"; break;
		case 3: cout << "Иди"; break;

	    }
    }
  
Задание 2

    #include<iostream>
    using namespace std;

    int main() {
	setlocale(LC_ALL, "Russian");
	int n;
	cin >> n;
	if(n % 2 == 0) cout << "Сегодня повезёт";
	else cout << "Лучше не рисковать";
    }

Задание 3

    #include<iostream>
    using namespace std;

    int main() {
	setlocale(LC_ALL, "Russian");
	int a, b, op;
	cin >> a >> b >> op;
	if (op == '+') {
		cout << a + b;
	}
	else if (op == '-') {
		cout << a - b;
	}
	else if (op == '*') {
		cout << a * b;
	}
	else if (op == '/') {
		if (b == 0) {
			cout << "Делить на ноль нельзя!";
		}
		else {
			cout << a / b;

			}
		}
	}

Задание 4

    #include<iostream>
    using namespace std;

    int main() {
	setlocale(LC_ALL, "Russian");
	int n;
    cin >> n;
    if(n < 0) cout << "Мороз";
    else if(n >= 0 && n <=20) cout << "Прохладно";
    else if(n >= 21 && n <= 30) cout << "Тепло";
    else if(n > 30) cout << "Жара";

Уровень 2

Задание 5
    
    #include<iostream>
    using namespace std;

    int main() {
    setlocale(LC_ALL, "Russian");
    int N;
    cin >> N;
    int sum = 0;
    for(int i = 1; i <= N; ++i) {
    sum += i;
    }
    cout << sum;
    }

Задание 6

    #include<iostream>
    using namespace std;

    int main() {
    setlocale(LC_ALL, "Russian");
    int N;
    cin >> N;
    for(int i = 1; i <= 10; ++i) {
    int n = i * N;
    cout << i << ' ' << '*' << N << ' ' << '=' << ' ' << n << endl;
      }
    }

Задание 7

    #include<iostream>
    using namespace std;

    int main() {
    setlocale(LC_ALL, "Russian");
    int N;
    cin >> N;
    int i = 1;
    while(N > i) {
    --i;
    cout << i << ' ';
      }  
    }

Задание 8

    #include<iostream>
    using namespace std;

    int main() {
    setlocale(LC_ALL, "Russian");
    int number;
    cin >> number;
    int counter = 0;
    while(number > 0) {
    number /= 10;

    counter++;
    }
    cout << counter;
    }

Уровень 3

Задание 9

     #include<iostream>
    using namespace std;

    int main() {
    setlocale(LC_ALL, "Russian");
    int n;
    cin >> n;
    int sum = 0;
    for(int i = 1; i <= n; ++i) {
    if(i % 2 == 0) {
    sum += i;
    }
    cout << sum;
    }
    }

Задание 10

    #include<iostream>
    using namespace std;

    int main() {
    setlocale(LC_ALL, "Russian");
    int numbers;
    cin >> numbers;

    int max = numbers;
    while(numbers != 0) {
    cin >> numbers;
    }
    if(numbers > max) {
    max = numbers;
    }
    cout << max;
    }

Задание 11

    #include<iostream>
    #include<random>
    using namespace std;

    int main() {
    setlocale(LC_ALL, "Russian");
    int x = rand() % 100 + 1;
    int n;
    cin >> n;
    if(n > x) cout << "Больше";
    else if(n < x) cout << "Меньше";
    else if(n == x) cout << "Вы угадали число!";

Уровень 4

Задание 12

    #include <iostream>
    using namespace std;

    int main() {
    setlocale(LC_ALL, "Russian");
    int n;
    cin >> n;
 
     if (n <= 1) {
     cout << "Не простое" << endl;
     return 0;
    }
 

     bool isprimeNumber = true;
     for (int i = 2; i * i <= n; i++) {
     if (n % i == 0) {
     isprimeNumber = false;
     break;
    }
    }
 

     if (isprimeNumber) {
     cout << "Простое" << endl;
    }    
    else {
     cout << "Не простое" << endl;
      }
    }

Задание 13

    #include <iostream>
    using namespace std;

    int main() {
    setlocale(LC_ALL, "Russian");
    int n;
    cin >> n;
    for(int i = 1; i <= n; ++i) {
    cin >> n;
    }
    for(int j = n; j >= 1; --j) {
    cout << n;
      }
    }
    



Задание 15

    #include <iostream>
    using namespace std;

    int main() {
    setlocale(LC_ALL, "Russian");
    int c;
    cin >> c;

    for(int i = 1; i <= c; ++i) {
      for(int j = 1; j <= i; ++j) {
      cout << '*';
      }
      cout << endl;
        }
      }

    

   
    
    
    

  

    
    


    
    
    


    


	



