#include <stdio.h>
#include <math.h>

         float log1 (float x) {
          return log (x)/log (10);
          }
          float f (float x) {
                return x* log1(x) - 1;
                }
    int main () {
        int d, i;
        float e, erro, a, b, m;
        
        do {
            printf (" \t Metodo da Bissecao \n\n");
            
            i=0; 
            printf("\n Entre com o erro -> 'e'= ");
            scanf ("%f", &erro);
            
            printf ("\n Qual o valor inicial -> 'a0' = ");
            scanf("%f", &a);
            
            printf("\n Qual o valor final -> 'b0' = ");
            scanf("%f", &b);
            
                     if (f(a)* f(b)<0){
                               do{
                               m = (a+b)/2;
                               printf("\n O valor de a_%d = %.4f e  b_%d = %.4f.", i, a, i, b);
                               printf ("\nO valor de f(a_%d) = %.4f e f(b_%d) = %.4f.", i, f(a), i++, f(b));
                               if(f(m)== 0){
                                         printf("\n\n A solucao sera %.4f.", m);
                                         break; 
                                         }
                                         else 
                                         if(f(m)*f(b)<0){
                                              a = m; }
                                              else {
                                                   b = m;}
                                                   e = fabs (b-a)/fabs(b);
                                                   printf("\n A %d iteracao  m = %.4f e f(m) = %.4f, com erro igual a %.4f\n.",i, m, f(m), e);
                                                   }while (erro <e);
                                                   m = (a+b)/2;
                                                   printf ("\n A solucao sera %.4f.", m);
                                                   }
                                                   else{
                                                   printf("\n Os pontos a0 e b0 nao satisfazem a condicao do metodo da bissecao.");}
                                                   printf("\n");
                                                   printf("\n\n Quer fazer para outros valores?\n\n Aperte 1 para refazer ou qualquer outra tecla para sair");
                                                   scanf("%d", &d);}
                                                   while (d==1);{
                                                   }
                                                   }
                
    
