# Basico de Kotlin

<p> Kotlin é uma linguagem de programação de código aberto estática, 100% compativel com Java, além de ter interoperátibilidade com outras linguagens como exemplo o javascript.</p>

detalhe importante

~~~
fun main(){

}
~~~
A função main é o primeiro código a ser executado no seu programa, é o ponto de entrada, através dela que começa a execução de tudo.

- Variavéis
    existem variavéis de muitos tipos, elas se dividem entre:

Mutavéis - que podem receber um novo valor
    var
Imutavéis
    val - não se alteram

-- Tipos de dados
    para tratar de variavéis ou parâmetros é sempre bom especificar seu tipo.

* Double  //  64
* Float   //  32
* Long    //  64
* Int     //  32
* Short   //  16
* Byte   //   8
* Boolean //  ?
* String 
* Char

em frente estão os bits, significa a capacidade de armazenamento que aquele dado permite, eles se separam por n° inteiros e decimais.

n° inteiros = Long, Int, Short, Byte
n° decimais = Double, Float

alguns recebem outros tipos de respostas

Boolean = False/True
String = palavras
Char = apenas um caractere

alguns desses dados pedem que sejam adicionados letra especificas a frente do numero, exemplo n° 10:
<p> Float = 10f
<p> Long = 10L
    
------------------------------------

Operadores aritméticos
    
    +  // soma
    -  // subtrai
    *  // multiplica
    /  // dividi
    %  // resto da divisão
   
-----------------------------------------    
    
### funções 

    funções se escrevem da seguinte forma
    
    declaração nomedafuncao ( variavel: tipo ) : retorno da função {
        ação
    }
    
    
    exemplo:
    
~~~
fun nomedafuncao(nome: String): String {
    return "Olá, $nome"
}
~~~

---------------------------------------------
    
 ### Controles de fluxo 
    
~~~
    if (condição) {
    println("Olá, MUndo!")
    }
~~~
    
Operador 
    
    - Comparação
    
    > maior
    < menor
    <= menor ou igual
    >= maior ou igual
    
    == igual
    != diferente
    ! negação
    
    - Lógicos
    
    && conjução ou "e"
    ││ disjunção ou "ou"
    
    
   - Ordem de execução
    
    Parênteses
    Negação
    Conjução
    Disjunção
    
