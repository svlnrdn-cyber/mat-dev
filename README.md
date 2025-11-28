<pre>
  #include <iostream>
#include <cmath>

using namespace std;

// f(x) = x^cos(x) fonksiyonun türevi f’(x) nedir?

double derivative_q3(double x)
{
    double term1 = cos(x) / x;
    double term2 = sin(x) * log(x);

    return pow(x, cos(x)) * (term1 - term2);
}

int main()
{
    double x_q3;

    //  x > 0 kontrolü
    while (true)
    {
        cout << "x'e (x > 0) olacak şekilde bir değer giriniz: ";
        if (cin >> x_q3 && x_q3 > 0)
        {
            break;
        }
        cout << "Hata! x pozitif bir sayı olmalıdı
</pre>
