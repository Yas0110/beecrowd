#include <iostream>
#include <iomanip>

int main() {
    
    int n_funcionario, n_horas;
    
    float v_hora, salario;
    
    std::cin >> n_funcionario >> n_horas >> v_hora;
    
    salario = n_horas * v_hora;
    
    std::cout << "NUMBER = " << n_funcionario << std::endl;
    
    std::cout << std::fixed << std::setprecision(2) << "SALARY = U$ " << salario << std::endl;
    
    return 0;
}
