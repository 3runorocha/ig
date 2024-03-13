SOLICITANDO O ARQUIVO DO INSTA:

> abra o site do instagram
> va no seu perfil
> va em configurações
> account center
> download your info
> download or transfer
> some of your info
> ai marca só followers and following
> download to device
> range all time
> formato html
> ai envtualmente voce vai receber um email avisando p baixar
> baixe o arquivo e abra o html

PASSO 1:

> abra o site: https://www.onlinegdb.com/online_c_compiler
> em "Standard Input:" marque a opção text
> volte para o html abra a aba followers ou following
> copie tudo abaixo de followers ou following até o final da pagina

////////////////////////////////////////////////////////////////////////
ex:
linha 1: Followers
linha 2: USUARIO
linha 3: Mar 5, 2024, 12:05 PM
...
linha n: Oct 22, 2011, 11:35 PM
copie entre a linha a linha 2 e n
////////////////////////////////////////////////////////////////////////

> volte para o gdb, e cole as linhas selecionadas na area "enter input to program here"
> apague a seção no site do gdb:
/******************************************************************************

                            Online C Compiler.
                Code, Compile, Run and Debug C program online.
Write your code in this editor and press "Run" button to compile and execute it.

*******************************************************************************/

#include <stdio.h>

int main()
{
    printf("Hello World");

    return 0;
}

> abra o passo 1 no github copie o codigo e cole na area que você acabou de apagar as linhas acima
> pressione o botão verde run
> abra o bloco de notas, salve com o nome followers/following, e cole TODAS as linhas que o programa retornou
> repita tudo mais uma vez dessa vez com a seção oposta da que você fez primeiro (se vez follower primeiro agora faça following)

PASSO 2:

> abra o gdb novamente, apague todas as linhas, selecione o input como texto
> copie todas as linhas de following e cole no input
> copie todas as linhas de followers e cole no input abaixo da ultima linha do following

////////////////////////////////////
ex:
primeiro usuario que você segue
ultimo seguidor

NÃO COLE ASSIM:
primeiro usuario que você segue

ultimo seguidor
////////////////////////////////////

> copie o codigo do passo 2 na area destinada pra codigo no gdb
> pressione o botão verde run
> salve o resultado em outro bloco de notas
> esse resultado vai corresponder a todos os usuarios unicos (se você segue um usuario e ele te segue de volta, ele se repete, deixando de ser unico)

PASSO 3:

> abra o gdb novamente, apague todas as linhas, selecione o input como texto
> copie todas as linhas de following e cole no input
> copie todas as linhas dos usuarios unicos obtidos e cole no input abaixo da ultima linha do following

////////////////////////////////////
ex:
ultimo seguidor que você segue
primeiro seguidor unico

NÃO COLE ASSIM:
ultimo seguidor que você segue

primeiro seguidor unico
////////////////////////////////////

> copie o codigo do passo 3 na area destinada pra codigo no gdb
> pressione o botão verde run
> salve o resultado em outro bloco de notas
> esse resultado vai corresponder a todos os usuarios unicos que você segue, ou seja, usuarios que VOCÊ segue, mas não te seguem de volta.

:)
