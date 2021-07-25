# 1) Divisibilidade
## 1.1) Definição 
Dados dois inteiros a e b, dizemos que "a divide b" e escreve-se a | b se existe um inteiro q ∈ ℤ tal que b = q ⋅ a. Alternativamente, a | b pode ser lido como "a é divisor de b" ou "b múltiplo de a". Quando a não divide b, escreve-se a ⫮ b. Por exemplo, temos que 3 | 15, mas 15 ⫮ 3.
→Observação: No intuito de evitar mal entendidos, é importante ressaltarmos que   a | b ≠ a  ⁄  b. A primeira expressão indica a relação de divisibilidade entre a e b; já a segunda indica a fração a ⁄ b, ou seja, a ÷ b.
 
## 1.2) Algumas propriedades relevantes
1. a | a         (reflexividade)
2. Se a | b e b | c, então a | c.       (transitividade)  
3. Se a | b e a | c, então a | bx + cy para qualquer combinação linear de b e c com coeficientes x e y ∈ ℤ. (linearidade)
4. Limitação: Se a | b, então b = 0 ou |a| ≤ |b|.
 
Demonstrações:
1. Como a = 1 ⋅ a, conclui-se que a | a.
2. Como a | b e b | c, existem q₁ e q₂ ∈ ℤ tais que b = aq₁ e c = bq₂, então c = aq₁q₂. Portanto, nota-se que a | c.
3. Como a | b e a | c, existem q₁ e q₂ ∈ ℤ tais que b = aq₁ e c = aq₂, assim bx + cy = aq₁x + aq₂y ⟹ bx + cy = a(q₁x + q₂y). Tendo em vista que (q₁x + q₂y) ∈ ℤ, concluímos que a | bx + cy.
4. Supondo que a | b e b ≠ 0, b = aq com q ≠ 0. Assim, |q| ≥ 1 e |b| = |a||q|.Então, |a| ≤ |b|.
 
## 1.3) Formas de descobrir se um número n é divisível por d:
### 1.3.1) CRITÉRIOS DE DIVISIBILIDADE
Um critério de divisibilidade é uma condição P necessária para que um número n seja divisível por d. Assim:
Um número inteiro n é divisível por d se, e somente se, a condição P for satisfeita.
➥Divisibilidade por 2:
Um número natural n é divisível por 2 se, e somente se, terminar em 0, ou 2, ou 4, ou 6, ou 8.
 
• JUSTIFICATIVA: Se n é um número natural da forma
n = aᵣ⋅10ʳ + aᵣ˗₁⋅10ʳ⁻¹ + ⋯ +a₂⋅10² + a₁⋅10¹ + a₀⋅10⁰, 
então podemos reescrevê-lo na forma n = 10⋅k + a₀,com k ∈ ℕ.
Como 10 é divisível por 2, então n será divisível por 2 se, e somente se, a₀ for divisível por 2. Como a₀ é um algarismo, a₀ será divisível por 2 se, e somente se, a₀ for 0, ou 2, ou 4, ou 6, ou 8.
Assim, n será divisível por 2 se, e somente se, terminar em 0, ou 2, ou 4, ou 6, ou 8.
 
➥Divisibilidade por 3:
Um número natural n é divisível por 3 se, e somente se, a soma de seus algarismos for divisível por 3.
 
• JUSTIFICATIVA:  Considere n o número natural abcde.
Assim, n = a⋅10⁴ + b⋅10³ + c⋅10² + d⋅10¹ + e⋅10⁰, com a ≠ 0.
Como 10⁴ = 10000 = 9999 + 1; 10³ = 1000 = 999 + 1; 10² = 100 = 99 + 1; 10¹ = 10 = 9 + 1; podemos reescrever n da seguinte forma:
n = a⋅(9999+1) + b⋅(999+1) + c⋅(99+1) + d⋅(9+1) + e 
n = 9999⋅a + a + 999⋅b + b + 99⋅c + c + 9⋅d + d + e 
ou ainda,
n = 3⋅(3333⋅a + 333⋅b + 33⋅c + 3⋅d) + (a + b + c + d + e) 
Agora, se k = (3333⋅a + 333⋅b + 33⋅c + 3⋅d) e t = (a + b + c + d + e), 
então n = 3⋅k + t, com  k, t ∈ ℕ.
Nesse caso, bastaria observar que n = 3⋅k + t é divisível por 3 se, e somente se, t for divisível por 3. 
Como t é a soma dos algarismos de n, então n é divisível por 3 se, e somente se, a soma de seus algarismos for divisível por 3.
 
➥Divisibilidade por 4:
Um número natural n, com mais de dois algarismos, é divisível por 4 se, e somente se, o número formado por seus dois últimos algarismos for divisível por 4.
 
• JUSTIFICATIVA: Se n é um número natural da forma
n = aᵣ⋅10ʳ + aᵣ˗₁⋅10ʳ⁻¹ + ⋯ +a₂⋅10² + a₁⋅10¹ + a₀⋅10⁰,
podemos reescrever n como
n = 100⋅k + (a₁⋅10 + a₀), com k ∈ ℕ,
já que 100 = 10² < 10³ < 10⁴ < ⋯ < 10ʳ⁻¹ < 10ʳ.
Assim, como 100 é divisível por 4, então n será divisível por 4 se, e somente se, a₁⋅10 + a₀ for divisível por 4.
Nota-se que a₁⋅10 + a₀ = a₁a₀, ou seja, o número cujo algarismo das unidades é a₀ e o das dezenas é a₁. Com isso, n será divisível por 4 se, e somente se, o número formado por seus dois últimos algarismos for divisível por 4.
 
➥Divisibilidade por 5:
Um número natural n é divisível por 5 se, e somente se, terminar em 0, ou 5.
 
• JUSTIFICATIVA: Seja n um número natural da forma
n = aᵣ⋅10ʳ + aᵣ˗₁⋅10ʳ⁻¹ + ⋯ +a₂⋅10² + a₁⋅10¹ + a₀⋅10⁰.
Se  k = aᵣ⋅10ʳ⁻¹ + aᵣ˗₁⋅10ʳ⁻² + ⋯ + a₂⋅10 + a₁,
podemos reescrever n como
n = 10⋅k + a₀, com k ∈ ℕ.
Assim, como 10 é divisível por 5, então n será divisível por 5 se, e somente se, a₀ for divisível por 5.
Como a₀ é um algarismo, então a₀ é divisível por 5 se, e somente se, a₀ = 0 ou a₀ = 5. Sendo a₀ o algarismo das unidades de n, então n será divisível por 5 se, e somente se, n terminar em 0 ou em 5.
 
➥Divisibilidade por 6:
Um número natural n é divisível por 6 se, e somente se, n for divisível, simultaneamente, por 2 e 3.
 
• JUSTIFICATIVA: 
Seja n um número natural. 
 
a)(⇒) Supondo que n seja divisível por 6. Assim, existe um número natural t de modo que n = 6⋅t. Observe que: 
⇨n = 6⋅t = 2⋅(3⋅t).      Se fizermos x = 3⋅t, então n = 2⋅x, com x ∈ ℕ, e assim n é divisível por 2.
⇨n = 6⋅t = 3⋅(2⋅t). Se fizermos, agora, z = 2⋅t, então n = 3⋅z, com z ∈ ℕ, e assim n é divisível por 3.
Logo, se n for divisível por 6, então n será divisível por 2 e por 3.
(“n divisível por 6” ⇒ “n divisível por 2 e por 3”)
 
b)(⇐) Supondo, agora, que n seja divisível por 2 e por 3. Como 2 | n, então existe k ∈ ℕ tal que n = 2⋅k.
 Note que 3 − 2 = 1, assim 3⋅k − 2⋅k = k, portanto 3⋅k − n =k   (i).
Por outro lado, existe também t ∈ ℕ tal que n = 3⋅t, pois 3 | n (ii).
Assim, por (i) e (ii) temos que k = 3⋅k − n = 3⋅k − 3⋅t = 3⋅(k−t).
Finalmente, se fizermos y = k − t, com k − t ≥ 0, então k = 3⋅y, com y ∈ ℕ.
Logo, n = 2⋅k = 2⋅(3⋅y) = 6⋅y, com y ∈ ℕ e isso garante que n é divisível por 6.
Concluímos, portanto, que se n for divisível por 2 e por 3, então n será divisível por 6.
(“n divisível por 2 e por 3” ⇒ “n divisível por 6”)
 
Por (a) e (b), chegamos ao critério.
 
➥Divisibilidade por 8:
Um número natural n, com mais de três algarismos, é divisível por 8 se, e somente se, o número formado por seus três últimos algarismos for divisível por 8.
 
• JUSTIFICATIVA: Seja n um número natural da forma
 n = aᵣ⋅10ʳ + aᵣ˗₁⋅10ʳ⁻¹ + ⋯ + a₃⋅10³ + a₂⋅10² + a₁⋅10¹ + a₀⋅10⁰,
então podemos reescrever n como
n = 1000⋅k + (a₂⋅10² + a₁⋅10 + a₀), com k ∈ ℕ,
já que 1000 = 10³ < 10⁴ < 10⁵ < ⋯ < 10ʳ⁻¹ < 10ʳ. Como 1000 é divisível por 8, então n será divisível por 8 se, e somente se, 100⋅a₂+10⋅a₁+a₀ for divisível por 8.
Perceba que 100⋅a₂+10⋅a₁+a₀ = a₂a₁a₀ é o número cujo algarismo das unidades é a₀, o das dezenas é a₁ e o algarismo das centenas é a₂, assim n será divisível por 8 se, e somente se, a₂a₁a₀ for divisível por 8.
Isso significa que n será divisível por 8 se, e somente se, o número formado por seus três últimos algarismos for divisível por 8.
 
➥Divisibilidade por 9:
Um número natural n é divisível por 9 se, e somente se, a soma de seus algarismos for divisível por 9.
 
• JUSTIFICATIVA: Considere n o número natural abcde. Assim, n = a⋅10⁴ + b⋅10³ + c⋅10² + d⋅10¹ + e⋅10⁰, com a ≠ 0.
Como 10⁴ = 10000 = 9999 + 1; 10³ = 1000 = 999 + 1; 10² = 100 = 99 + 1; 10¹ = 10 = 9 + 1; podemos reescrever n assim:
n = a⋅(9999 + 1) + b⋅(999 + 1) + c⋅(99 + 1) + d⋅(9 + 1) + e 
n = 9999⋅a + a + 999⋅b + b + 99⋅c + c + 9⋅d + d + e, 
ou
n = 9⋅(1111⋅a + 111⋅b + 11⋅c + 1⋅d) + (a + b + c + d + e).
Se k = 1111⋅a + 111⋅b + 11⋅c + 1⋅d  e  t = a + b + c + d + e, então
n = 9⋅k + t, com  k, t ∈ ℕ.
Nesse caso, bastaria observar que n = 9⋅k + t é divisível por 9 se, e somente se, t for divisível por 9. Como t é a soma dos algarismos de n, então n é divisível por 9 se, e somente se, a soma de seus algarismos for divisível por 9.
 
➥Divisibilidade por 10:
Um número natural n é divisível por 10 se, e somente se, terminar em 0.
 
• JUSTIFICATIVA: Seja, então, n um número natural da forma
n = aᵣ⋅10ʳ + aᵣ˗₁⋅10ʳ⁻¹ + ⋯ +a₂⋅10² + a₁⋅10¹ + a₀⋅10⁰.
Se k = aᵣ⋅10ʳ⁻¹ + aᵣ˗₁⋅10ʳ⁻² + ⋯ + a₂⋅10 + a₁, podemos reescrever n como
n = 10⋅k + a₀, com k ∈ ℕ.
Assim, como 10 é divisível por 10, então n será divisível por 10 se, e somente se, a₀ for divisível por 10.
Mas a₀ é um algarismo, portanto a₀ é divisível por 10 se, e somente se, a₀ = 0. Como a₀ é o algarismo das unidades de n, então n será divisível por 10 se, e somente se, n terminar em 0.
1.3.2) ANÁLISE DA DECOMPOSIÇÃO EM FATORES PRIMOS
Uma forma eficaz de encontrar os divisores de um número natural n, n > 1, é analisando a sua decomposição em fatores primos.
Exemplificando:
504 = 2³⋅3²⋅7.
⇾504 é divisível por 2? 
Sim, pois 504 = 2⋅(2²⋅3²⋅7). Então, 504 = 2k, com k ∈ ℕ.
⇾504 é divisível por 3?
Sim, pois 504 = 3⋅(2³⋅3⋅7). Então, 504 = 3z, com z ∈ ℕ.
⇾504 é divisível por 21?
Sim, pois 504 = 3⋅7⋅(2³⋅3). Então, 504 = 21w, com w ∈ ℕ.
⇾504 é divisível por 5?
Não, pois sua decomposição não apresenta o fator primo 5.
⇾504 é divisível por 252?
Sim, pois 504 = (2²⋅3²⋅7)⋅2. Ou seja, 504 = 252⋅2.
 
 
 
 
# 2) Primos
Um conceito importante baseado na divisibilidade é o do número primo. Os primos se tornaram essenciais nos sistemas de criptografia modernos, a quantidade de tempo necessária para fatorar grandes inteiros entre os seus fatores primos é a base para a força de alguns dos sistemas de criptografia modernos.
Por definição, um inteiro p maior que 1 é chamado de primo se os únicos fatores positivos de p são 1 e p. Um inteiro positivo que é maior que 1 e não é primo é chamado de composto. O número 1 não é primo porque ele só tem um fator positivo, já o inteiro 7 é primo porque os únicos fatores positivos dele são 1 e 7, enquanto o inteiro 9 é composto porque é divisível por 3.
## 2.1) Teorema fundamental da aritmética e a divisão por tentativa
Os números primos são as bases dos inteiros positivos, como provado no teorema fundamental da aritmética. Segundo o teorema, todo inteiro maior que 1 pode ser escrito unicamente como um primo ou como o produto de dois ou mais primos. O número 840, por exemplo, derivado da multiplicação dos primos 2, 3, 5 e 7, e pode ser fatorado como 23357.
Além disso, se um número n é um inteiro composto, então ele tem um divisor primo menor ou igual a n. Isso leva ao algoritmo de força bruta conhecido como divisão por tentativa, no qual n é dividido por todos os primos que não excedam n, e conclui-se que n é primo se ele não for divisível por nenhum desses primos. Por exemplo, os únicos primos que não excedem o valor 101 (aproximadamente 10,05) são 2, 3, 5 e 7, e como 101 não é divisível por nenhum destes, então 101 é primo.
## 2.2) O Crivo de Eratóstenes
Os inteiros compostos até 100 devem ter fatores primos menores que 10, e esses são somente 2, 3, 5, e 7, então todos os números primos que não excedem 100 são esses quatro primos e os números maiores que 1 não divisíveis por eles.
O Crivo de Erastótenes é um algoritmo usado para achar todos os primos que não excedem um número inteiro positivo dado. No processo, os inteiros que forem divisíveis por 2, fora o 2, são excluídos. Como o 3 é o próximo inteiro, os números que forem divisíveis por 3 são excluídos, e por conta do 4 ter sido excluído durante o processo de divisão por 2, o próximo inteiro é o 5. Isso se repete para os números seguintes, restando somente os números primos menores que 100, sendo esses os números 2, 3, 5, 7, 11, 13, 17, 19, 23, 29, 31, 37, 41, 43, 47, 53, 59, 61, 67, 71, 73, 79, 83, 89, e 97.
### 2.2.1) Implementação em C
Uma das maneiras de implementar o algoritmo do Crivo de Erastótenes utilizando a linguagem de programação C, é a seguinte:

```C
#include <stdio.h>
#include <stdlib.h>
 
int main()
{
    int num, i, j;
    printf("Digite o número limite para a sequência de primos\n");
    scanf("%d", &num);
 
    // Cria um vetor primos com tamanho dinâmico definido por num
    int *primos = malloc(num * sizeof(*primos));
 
    // Preenchendo o vetor primos com números naturais
    for (i = 2; i <= num; i++)
        primos[i] = i;
 
    i = 2;
    while ((i*i) <= num)
    {
        if (primos[i] != 0)
        {
            /* Exclui os múltiplos de cada valor,
            começando por 2, passando por 3, depois
            por 5 (porque o 4 já estará excluído),
            e assim por diante */
 
            for (j = 2; j < num; j++)
            {
                /* Se o valor da multiplicação passar do
                número limite, o looping se encerra */
 
                if (primos[i]*j > num)
                    break;
                else
                    // Marca o valor que não é primo como 0
                    primos[primos[i]*j] = 0;
            }
        }
        i++;
    }
 
    for (i = 2; i <= num; i++)
    {
        // Imprimindo números que não estão marcados como 0
        if (primos[i] != 0)
            printf("%d\n",primos[i]);
    }
 
    return 0;
}
```

## 2.3) A infinidade dos números primos
Em seu famoso texto, Os Elementos, Euclides provou de uma forma simples que existem infinitos números primos, e esse teorema foi provado utilizando o argumento do absurdo.
Supondo que a sequência dos primos seja finita, p1,p2,…,pn é a lista de todos os primos. Logo, considera-se o número R=p1·p2pn+1. Pelo teorema fundamental da aritmética, todo número composto maior que 1 é representado como um produto de fatores primos. No entanto, nenhum dos primos pi divide R, e se pi é um fator de R, então pi divide R–p1·p2pn=1, constatando que existe um primo que não está na lista, sendo ele R ou um outro fator primo de R. É uma contradição criada pela presunção de que todos os primos foram listados, consequentemente, existem infinitos números primos.
# 3) MDC (Máximo divisor comum) 
Como já visto anteriormente, os conceitos de divisibilidade são extremamente importantes na matemática. Dessa forma, aqui iremos continuar estudando alguns conceitos fundamentais ligados ao tema. Em específico, falaremos sobre o MDC.
## 3.1) Definição
Como visto anteriormente, sabemos que para dados três números inteiros e não-nulos a, b e c, dizemos que c é divisor de a e b se, e somente se,  c|a e c|b. Partindo desse conceito, seja o conjunto D(a,b) formado por todo divisor comum de a e b, definimos mdc(a,b) como sendo o maior valor de D. De forma mais rigorosa, podemos dizer que:

Sejam:
{a, b, c} ⊂ Z

Definimos:
mdc(a,b) = max(c : c ∊ D)

Onde:
D={c : c|a e c|b }

Seguindo a mesma ideia, podemos ainda generalizar o conceito de MDC para mais de dois números. Nesse caso, para definirmos o maior divisor comum de n termos bastaria definirmos o conjunto D como sendo formado pelos inteiros que dividem simultaneamente todos esses números. Assim, o MDC deles seria o maior elemento de D.
## 3.2) Cálculo do MDC
Agora que definimos o que é o MDC, precisamos falar sobre diferentes formas para calcularmos ele. Esse tema é extremamente importante pois, como veremos adiante, as formas mais avançadas, embora um pouco mais difíceis de serem compreendidas, são extremamente eficientes.
### 3.2.1) Cálculo pela definição
Seguindo a definição fornecida anteriormente, caso desejemos calcular o MDC de dois números, como 30 e 20, podemos realizar o seguinte algoritmo:

Monte o conjunto dos divisores do primeiro número: D(20) = {1,2,4,5,10,20}

Monte o conjunto dos divisores do segundo número: D(30) = {1,2,3,5,6,10,15,30}

Monte o conjunto dos divisores comuns: D(30,20) = {1,2,5,10}


Dessa forma, pegando o maior valor do último conjunto, teríamos que mdc(20,30)=10.

Apesar de correto, o procedimento foi pouco eficiente. Dessa forma, agora falaremos sobre outras formas mais interessantes para se obter o mesmo resultado. 

### 3.2.2) Cálculo pela fatoração de primos
O método dos fatores primos provavelmente é o algoritmo mais conhecido para o cálculo do MDC. A ideia aqui é simples: realize o processo de decomposição em primos dos números cujo MDC você quer calcular e multiplique os primos que dividiram ambos os números. 

Aplicando tal lógica ao exemplo dado anteriormente, temos:


Aqui, como “2” e “5” dividiram ambos os números, temos:

Vale ainda ressaltar que, assim como no método anterior, aqui você também pode calcular o MDC de mais de dois números ao mesmo tempo. Para isso, basta seguir o mesmo procedimento e pegar o produto dos fatores primos que dividiram todos os números.








### 3.2.3) Cálculo pelo algoritmo de Euclides
O algoritmo de Euclides é um método extremamente interessante e eficiente para calcular o MDC entre dois números. Na realidade, acredita-se que o mesmo foi criado cerca de 2300 anos atrás, antes mesmo da criação da álgebra, em uma época na qual os gregos usavam comprimentos para representar números.

A principal ideia do algoritmo em questão o fato que, para dados a e b inteiros, temos que:

onde:

com:
 


Em um primeiro momento esse algoritmo pode parecer pouco útil, uma vez que nosso objetivo era calcular o mdc(a,b) e agora temos que calcular outro  MDC. Contudo, a ideia aqui é que usaremos tal algoritmo de forma recursiva, até que o termo da direita seja do tipo mdc(k,0) (sendo tal valor obviamente igual a k).

Aplicando este algoritmo no exemplo dado anteriormente, temos que:

Como:

segue:


 

Para o cálculo do MDC de mais de dois números por meio deste algoritmo basta aplicá-lo mais de uma vez. Ou seja, para o cálculo de mdc(a,b,c), por exemplo, basta descobrir o valor de: mdc(mdc(a,b),c). 

## 3.3)Propriedades elementares
Visando complementar nosso estudo, o presente capítulo irá abordar algumas propriedades relacionadas ao MDC de dois ou mais números. Naturalmente uma conversa aprofundada sobre o tema sairia totalmente do escopo deste trabalho, então buscaremos tratar de algumas propriedades mais básicas, mas que também são extremamente importantes.
 
### 3.3.1)Propriedade 01
Tese:



Demonstração:

Seguindo a definição exposta em 3.1, o MDC de dois números é definido como o maior termo do conjunto formado pelos divisores comuns de “a” e “b”. Sendo assim, temos:



Contudo, também é fácil ver que:

Uma vez que:


### 3.3.2)Propriedade 02
Tese:

“Para todo ‘a’ e ‘b’ inteiros, podemos afirmar que mdc(a,b) é sempre maior ou igual a 1”.

Demonstração:

A demonstração desse fato é trivial. Sendo o número 1 divisor de qualquer outro número, então ele sempre estará no conjunto dos divisores de ‘a’ e ‘b’. Assim, o maior termo desse conjunto nunca será menor que 1.

### 3.3.3)Propriedade 03
Tese:
“Para todo inteiro positivo ‘a’, vale dizer que mdc(a,0) = a”.

Demonstração:

Comecemos montando o conjunto D(a,0) dos divisores de “a” e “0”:



Aqui usemos do fato que todo inteiro não nulo divide o número zero, assim:


Assim, vê-se que :


Dessa forma, temos que:

Em derivação desses fatos, e considerando que o maior elemento de D(a) é o próprio “a”, segue que:

## 3.4)Análise computacional
Visando complementar o estudo desenvolvido até o momento, o presente capítulo buscará discorrer sobre aplicações computacionais de alguns dos algoritmos comentados. A linguagem utilizada em questão será C++, mas adiantamos que teremos como foco a lógica computacional, e não a sintaxe da linguagem. Dessa forma, mesmo que o leitor não tenha conhecimento sobre a mesma, é fato que ele tirará grande proveito da leitura do presente capítulo.

### 3.4.1)Cálculo pela definição
O primeiro método abordado irá calcular o MDC de dois números fornecidos pelo usuário usando da definição exposta anteriormente. Caso o leitor queira rever a teoria matemática por trás do mesmo, basta rever as ideias expostas na seção 3.2.1. Posto isso, segue o código comentado abaixo:

```C++
//Importamos as bibliotecas relevantes:
#include <bits/stdc++.h>
 
using namespace std;
 
//Declaramos a função principal:
int main(){
    // Declaramos nossos inteiros e fazer a leitura dos mesmos:
    int a,b;
    cin>>a>>b;
 
    // Declaramos os vetores que irão guardar os divisores:
    vector <int> divisores_de_a, divisores_de_b, divisores_de_ab;
 
    // Pegamos os divisores de "a":
    for(int i=1;i<=a;i++){
        if(a%i==0){
            divisores_de_a.push_back(i);
        }
    }
 
    // Pegamos os divisores de "b":
    for(int i=1;i<=b;i++){
        if(b%i==0){
            divisores_de_b.push_back(i);
        }
    }
 
    // Pegamos os divisores de "a" e "b":
    for(int i=0;i<divisores_de_a.size();i++){
        for(int j=0;j<divisores_de_b.size();j++){
            if(divisores_de_a[i]==divisores_de_b[j]){
                divisores_de_ab.push_back(divisores_de_a[i]);
            }
        }
    }
 
    // Mostramos para o leitor o maior divisor de "a" e "b":
    cout<<divisores_de_ab[divisores_de_ab.size()-1];
    
    return 0;
}
```


### 3.4.2)Cálculo pelo algoritmo de Euclides
Nosso segundo código também receberá dois números do usuário e irá calcular o MDC entre eles, mas agora tal valor será obtido pelo algoritmo de Euclides. Caso o leitor queira rever a teoria por trás deste método, basta visitar a seção 3.2.3. Dessa forma, segue o código comentado:

```C++
//Importamos as bibliotecas relevantes:
#include <bits/stdc++.h>
 
using namespace std;
 
// Definimos a função que irá retornar o MDC:
int mdc(int a, int b){
    // Caso o termo da direita seja "0", a função retorna o termo da esquerda:
    if(b == 0){
        return a;
    }
    // Caso a condição anterior seja falsa, a função vai chamar a si mesma,mas
    // agora ela trocará as variáveis "a" e "b" por "b" e "a%b", sendo essa
    // última o resto da divisão de "a" por "b": 
    return mdc(b, a%b);
}
 
int main(){
    // Aqui declarmos "a" e "b" e fazemos a leitura dos mesmos:
    int a,b;
    cin>>a>>b;
    // Retornamos para o usuário o valor calculado pela função mdc:
    cout<<mdc(a,b);
    return 0;
}
```


# 4) Aritmética Modular
## 4.1) Definição

A operação módulo é definida como o resto da divisão de um certo número a por M= r ou seja:

a (mod M) = r	Sendo a,rZ e M  N.

Ele também pode ser na forma de divisão:

a = Mk + r	Sendo k um inteiro qualquer
Exemplificando, podemos ter 13 mod 5 13=52 + 3, ou seja, o resto da divisão de 13 por 5 é igual a 3.
## 4.2) Congruências
### 4.2.1) Definição
A partir da definição de módulo podemos definir o conceito de congruência, onde dizemos que

ab (mod M) se a (mod M) = b (mod M)

Ou seja, ambos compartilham o mesmo resto divididos por M.
### 4.2.2) Propriedades da Congruência
Se ab (mod M) e cd (mod M), logo:

a+cb+d (mod M)
acbd (mod M)

Por exemplo, se temos 72 (mod 5) e 111 (mod 5), segue-se que:

7+112+1 (mod 5) ---> 183 (mod 5) e
71121 (mod 5) ----> 772 (mod 5)
## 4.3) Propriedades dos módulos
Voltando ao módulo, temos mais algumas propriedades:
Sejam MN e a,bZ , temos:

a (mod M)=a+kM (mod M)	Sendo k um inteiro qualquer
 a+b (mod M)=[a (mod M)+b(mod M)] mod M
 	    		 ab (mod M)=[a (mod M)b(mod M)] mod M

Utilizando a primeira propriedade podemos encontrar vários números que dão o mesmo resto, como por exemplo:

-1 (mod 3)= -1+k3 (mod 3) = 2 (mod 3)=5 (mod 3)=8 (mod 3) ... = 2

As outras duas propriedades nos auxiliarão a descobrir módulos mais difíceis de se calcular, com somas e expoentes grandes.




### 4.3.1) Exemplo 1
Calcule 1234567 (mod 11):

Podemos decompor o número 1234567 como:

10⁶+210⁵+310⁴ + 410³ + 510² + 610 + 7

 Dessa forma, aplicando a propriedade da soma que vimos acima, temos:

[10⁶mod11+210⁵mod11+310⁴mod11 + 410³mod11+
 + 510²mod11 + 610mod11 + 7mod11] mod 11

Para as potências de 10, devemos encontrar um padrão:

10¹ (mod 11)=-1 Pois: 10=111-1
10² (mod 11)=1010 (mod 11) = -1-1=1
10³ (mod 11)=10²10 (mod 11) = 1-1=-1
…
O padrão se repete, então podemos afirmar que se n é par, 10n(mod 11)=1, e se n é ímpar, 10n(mod 11)=-1

Logo, temos:
[1-2+3-4+5-6+7] mod 11=
4 mod 11=4
4.3.1) Exemplo 2
Calcule 5143 (mod 7)

Para este exercício não precisamos gastar tempo calculando 5143 que é um número absurdamente grande, só precisamos utilizar o módulo de uma das potências na próxima, até achar uma potência que dá resto 1, ou seja, todas as potências subsequentes desta vão dar resto 1 também.

Primeiramente devemos enxergar um padrão nas potências de 5:

5 (mod 7)=5
5² (mod 7)=25 (mod 7) = 4
5³ (mod 7)=(255) (mod 7) = (25 mod 75 mod 7) mod 7 = 45 mod 7 = 6
5⁴ (mod 7)=5³5 (mod 7) = 65 (mod 7) = 2
5⁵ (mod 7)=5⁴5 (mod 7) = 25 (mod 7) = 3
5⁶ (mod 7)=35 (mod 7) = 1

Já podemos parar no 1, visto que 5⁶ (mod 7)=1, logo (5⁶)n sempre vai ser 1, então podemos reescrever o exercício como:

(5⁶)235⁵ (mod 7) = 15⁵ (mod 7). 
Como calculado anteriormente, 5⁵ (mod 7)=3

4.4) Pequeno Teorema de Fermat
4.4.1) Definição
Se pN,p é primo, então: 
ap-1 (mod p) = 1
Ou também: 	ap-1-11 (mod p)

Podemos utilizar esta propriedade para calcular as potências de uma maneira bem mais fácil, visto que ela irá mostrar de primeira a potência que deixa resto 1. Lembrando que somente deve ser utilizada se p for primo.
### 4.4.2) Exemplo
calcule 7149 (mod 37)

Pelo teorema, podemos chegar diretamente em:

736 (mod 37) = 1

Logo, podemos reescrever a expressão dada como: 

(736)47⁵ (mod 37)=7⁵ (mod 37)

Que fica bem mais fácil calcular do que escrever 36 potências seguidas até chegar no 736 (mod 37)= 1.

7⁵ (mod 37)=49497 (mod 37)
12127 (mod 37)=1210 (mod 37)=9


## 4.5) Programa em C que calcula ae (mod d):
No programa abaixo, você deve passar os parâmetros a, e, d para calcular o resultado de ae (mod d)

```C
#include <stdio.h>
 
unsigned int mod(int a, int e, int d){
   int mod = 1;
 
   for(int i=0;i<e;i++){
       mod = a*mod % d;
   }
 
   return mod;
}
 
int main(){
 
   unsigned int a, e, d;
 
   scanf("%d %d %d", &a, &e, &d);
 
   int x;
   x = mod(a,e,d);
 
   printf("%d\n", x);
	
   return 0;
}
```

O programa basicamente calcula o módulo utilizando o resultado do módulo anterior, demonstramos lá atrás como fazer isso, ele calcula o módulo “e” vezes, que é a potência do número dado.
Se utilizarmos o programa sem calcular o módulo número por nuḿero, elevando o número à potência e tirando o módulo, é bem capaz que a variável dê um overflow, visto que muitas vezes o número vai ser absurdamente grande, logo, é mais viável calcular o novo módulo utilizando o módulo anterior.

Exemplos de casos de teste:<br/>
a=343,e=343,d=7387		Saída: 6385<br/>
a=7,e=1001,d=11		Saída: 7<br/>
a=4,e=1004,d=9			Saída: 7<br/>
a=17452,e=1,d=11		Saída: 6
