-----
# Progrmação Orientada a Objeto
-----

<div align="justify">
## Projeto - Avaliação 2
<p>
É um projeto de POO realizado para a AV2 utilizando o Banco de Dados local e os critérios informados abaixo.
</p>

### Parte 1: Implementação das Entidades (10pts)
<p>
• Você receberá um diagrama de classes com duas classes que possuem uma associação um-para-muitos entre elas. Seu objetivo é implementar o código em Java para essas classes, seguindo as melhores práticas de orientação a objetos. <br />
• Garanta que todos os campos das classes sejam encapsulados corretamente. Utilize modificadores de acesso apropriados e forneça métodos de acesso (getters) e modificação (setters) quando necessário. <br />
Crie um construtor vazio (sem argumentos) para cada classe que inicialize os campos com valores padrão apropriados. <br />
Crie também um construtor para cada classe que aceite argumentos para inicializar todos os atributos da classe. Certifique-se de validar os valores passados nos construtores. <br />
• Implemente o método `toString()` em ambas as classes para que ele retorne uma representação em formato de string das informações contidas nas classes. Certifique-se de incluir todas as informações relevantes. <br />
Implemente o método `equals(Object obj)` nas classes para que ele compare as instâncias das classes com base em critérios apropriados. <br />
Implemente o método `hashCode()` nas classes para que ele gere um código hash único para cada instância, considerando os campos relevantes para a comparação. <br />
Considerando que a igualdade deve ser baseada no id das entidades. <br />
</p>

### Parte 2: Mapeamento Objeto-Relacional (15pts)
<p>
<b>Faça o mapeamento objeto-relacional das classes para uma tabela no banco de dados, seguindo as regras abaixo:</b> <br />
<br />
• As tabelas devem possuir o prefixo “tbl_”. Por exemplo: “tbl_customer”, “tbl_order”. <br />
• Colunas “id” devem possuem o seguinte padrão “<nome da classe>_id”. Por exemplo: “customer_id”, “order_id”. <br />
• Colunas “nome” devem possuir o prefixo “nom_”. Por exemplo: “nom_customer”. <br /> 
• Colunas “telefone” devem possuir o prefixo “tel_”. Por exemplo: “tel_customer”. <br />
• Colunas “data” devem possuir o prefixo “dt_”. Por exemplo: “dt_nascimento”. <br />
</p>

### Parte 3: Operações CRUD (15pts)

<p>
<b>Implemente as operações CRUD (Criar, Consultar, Atualizar e Excluir) para a classe Aggregate, que é a classe principal. Siga as especificações a seguir:</b> <br />
<br />
• O projeto deve incluir um ponto de execução "public static void main". <br />
• No método "criar", você deve criar objetos das duas classes. Utilize a opção "CASCADE PERSIST" para inserir os registros em ambas as tabelas. <br />
• No método "consultar", recupere o objeto pelo seu ID e exiba as informações utilizando "System.out.println()". <br />
• No método "excluir", recupere o registro pelo ID e remova-o utilizando a opção "CASCADE DELETE", excluindo os registros das duas tabelas. <br />
• Critérios de Avaliação <br />
<br />
<b>Você será avaliado(a) com base nos seguintes critérios:</b> <br />
<br />
• Implementação correta das classes, incluindo os construtores, associações, métodos get/set, equals, hashCode e toString.<br />
• Código sem erro de compilação, bem-organizado e devidamente indentado.<br />
• Uso correto das convenções de nomenclatura em Java (CamelCase para nomes de classes e métodos, ALL_CAPS para constantes, etc.). <br />
• Correto mapeamento objeto-relacional das classes no banco de dados. <br />
• Implementação correta das operações CRUD, considerando todas as especificações mencionadas. <br />
<img alt="EXERCICIO" src="https://github.com/joaovitorgfs/banco-de-dados/blob/main/SCRIPT%20-%2002/img/exercicio.png" /> <br />
</p>
</div>
