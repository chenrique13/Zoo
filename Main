import java.util.Scanner;

public class Main {

	public static void main(String[] args) {

		Scanner scanner = new Scanner(System.in);
		ColecaoDeAnimais colecao = new ColecaoDeAnimais();

		for (int x = 0; x < 5; x++) {

			System.out.println(" Escolha a Fun��o:  ");
			System.out.println(" 1 para Adicionar");
			System.out.println(" 2 para Remover");

			int funcao = scanner.nextInt();

			if (1 == funcao) {

				System.out.println(" Escolha o tipo do animal: ");
				System.out.println(" 1 para Cachorro");
				System.out.println(" 2 para Gato");
				System.out.println(" 3 para Passaro");
				System.out.println(" 4 para Outros");
				int tipo = scanner.nextInt();

				if (1 == tipo) {
					Cachorro c = new Cachorro();

					System.out.println("Digite o nome do cachorro: ");
					c.nome = scanner.next();
					System.out.println("Digite a ra�a do cachorro: ");
					c.raca = scanner.next();
					System.out.println("Digite a idade do cachorro: ");
					c.idade = scanner.nextInt();
					System.out.println("Digite a quantidade de patas do cachorro: ");
					c.qtdPatas = scanner.nextInt();
					System.out.println("Digite o peso do cachorro: ");
					c.peso = scanner.nextFloat();
					colecao.adicionar(c);
				} else if (2 == tipo) {
					Gato g = new Gato();

					System.out.println("Digite o nome do gato: ");
					g.nome = scanner.next();
					System.out.println("Digite a ra�a do gato: ");
					g.raca = scanner.next();
					System.out.println("Digite a idade do gato: ");
					g.idade = scanner.nextInt();
					System.out.println("Digite a quantidade de patas do gato: ");
					g.qtdPatas = scanner.nextInt();
					System.out.println("Digite o peso do gato: ");
					g.peso = scanner.nextFloat();

					colecao.adicionar(g);
				} else if (3 == tipo) {
					Passaro p = new Passaro();

					System.out.println("Digite o nome do passaro: ");
					p.nome = scanner.next();
					System.out.println("Digite a ra�a do passaro: ");
					p.raca = scanner.next();
					System.out.println("Digite a idade do passaro: ");
					p.idade = scanner.nextInt();
					System.out.println("Digite a quantidade de patas do passaro: ");
					p.qtdPatas = scanner.nextInt();
					System.out.println("Digite o peso do passaro: ");
					p.peso = scanner.nextFloat();
					colecao.adicionar(p);

				} else if (4 == tipo) {
					Animal a = new Outros();

					System.out.println("Digite o nome do animal: ");
					a.nome = scanner.next();
					System.out.println("Digite a ra�a do animal: ");
					a.raca = scanner.next();
					System.out.println("Digite a idade do animal: ");
					a.idade = scanner.nextInt();
					System.out.println("Digite a quantidade de patas do animal: ");
					a.qtdPatas = scanner.nextInt();
					System.out.println("Digite o peso do animal: ");
					a.peso = scanner.nextFloat();
					colecao.adicionar(a);

				} else {
					System.out.println("C�digo inesistente");
				}
			}
			colecao.listar();

			if (2 == funcao) {
				System.out.println("Qual o animal q vc quer excluir? ");
				int i = scanner.nextInt();
				colecao.remover(i);
				colecao.listar();
			}
		}

//		
//		
////		c.comunicar();
////		g.comunicar();
////		p.comunicar();
//		
//		ColecaoDeAnimais colecao = new ColecaoDeAnimais();
//		
//		colecao.adicionar(c);
//		colecao.adicionar(g);
//		
//		
//		colecao.adicionar(p);
//		colecao.listar();

//		System.out.println("Digite seu nome: ");
//		String nome = scanner.next();
//		
//		System.out.println("Digite seu sobrenome: ");
//		String sobrenome = scanner.next();
//		
//		System.out.println("Digite sua idade: ");
//		int idade = scanner.nextInt();
//		
//		System.out.println("Seu nome � " + nome + " "+ sobrenome + " e sua idade � " + idade + " anos.");

	}
}
