

# SmartTv

Nesse pequeno projeto desenvolvido para a pratica de atividades em Java para melhorar minhas habilidades de aprendizados em java pela DIO. 

## metodos ultilizados 

`Ligar smartTv` `Desligar smartTv`: Para Ligar/ Desligar a TV. 

 `aumentarVolume` `diminuirVolume`: Para ajustar o volume.

 `mudarCanal` : para mudar de canal 

Onde o desenvolvimento dos estudos acima levarão o metodos de um sistema simples de SmartTv. 



## Funcionalidades

- Ligar/Desligar.  
- aumentarVolume/diminuirVolume.
- mudar de canal 

## Variáveis de Ambiente

Para rodar esse projeto, você vai precisar adicionar as seguintes variáveis de ambiente no seu Compilador. 

` public class Usuario {
    public static void main(String[] args) throws Exception {
        SmartTv smartTv = new SmartTv();

        System.out.println("TV ligada ? " + smartTv.ligada);
        System.out.println("Canal Atual ? : " + smartTv.canal);
        System.out.println("Volume atual ? : " + smartTv.volume);
    
        smartTv.Ligar (); 
        System.out.println("Novo status -> TV ligada? " + smartTv.ligada);
        smartTv.desligar();
        System.out.println("Novo status -> TV ligada? " + smartTv.ligada);

        smartTv.diminuirVolume();
        smartTv.diminuirVolume();
        smartTv.diminuirVolume();
        smartTv.aumentarVolume();

        System.out.println("Volume Atual : " + smartTv.volume);

        smartTv.mudarCanal(13);
        System.out.println("Canal Atual ? : " + smartTv.canal);

    }
}`


## Autores

- [@Ivana-Gomes](https://www.github.com/Ivana-Gomes)

