## 📚 Atividade 1

### ENUNCIADO

> What precisely do we mean by software engineering? What distinguishes “software engineering” from “programming” or “computer science”? And why would Google have a unique perspective to add to the corpus of previous software engineering literature written over the past 50 years? The terms “programming” and “software engineering” have been used interchangeably for quite some time in our industry, although each term has a different emphasis and different implications. University students tend to study computer science and get jobs writing code as “programmers.” “Software engineering,” however, sounds more serious, as if it implies the application of some theoretical knowledge to build something real and precise. Mechanical engineers, civil engineers, aeronautical engineers, and those in other engineering disciplines all practice engineering. They all work in the real world and use the application of their theoretical knowledge to create something real. Software engineers also create “something real,” though it is less tangible than the things other engineers create. Unlike those more established engineering professions, current software engineering theory or practice is not nearly as rigorous. Aeronautical engineers must follow rigid guidelines and practices, because errors in their calculations can cause real damage; programming, on the whole, has traditionally not followed such rigorous practices. But, as software becomes more integrated into our lives, we must adopt and rely on more rigorous engineering methods. We hope this book helps others see a path toward more reliable software practices.

### RESPOSTA

A discussão apresentada é de grande importância, pois a falta de distinção entre Ciência da Computação, programação e Engenharia de Software pode gerar interpretações equivocadas sobre o desenvolvimento de sistemas. Embora essas áreas estejam diretamente relacionadas, cada uma possui objetivos e responsabilidades diferentes. A programação está mais relacionada à escrita de códigos e à implementação de soluções para determinados problemas. Já a Ciência da Computação envolve o estudo dos fundamentos teóricos e científicos da computação, como algoritmos, estruturas de dados e funcionamento dos sistemas. A Engenharia de Software, por sua vez, utiliza conhecimentos dessas áreas e aplica princípios de engenharia para desenvolver, organizar e manter softwares de maneira estruturada, buscando garantir qualidade, segurança e confiabilidade.

Nesse sentido, saber programar não significa necessariamente exercer plenamente a Engenharia de Software. Desenvolver um sistema vai muito além de fazer com que um código funcione. É preciso pensar em como ele será utilizado, quais problemas poderá apresentar, como será realizada sua manutenção e de que maneira poderá se adaptar às necessidades futuras. Isso exige planejamento, documentação, testes e acompanhamento durante todo o processo de desenvolvimento.

Outro ponto importante apresentado no texto é a comparação com outras áreas da engenharia, como a civil e a aeronáutica. Nessas profissões, existem normas e procedimentos bastante rigorosos, pois erros podem comprometer a segurança de muitas pessoas. Com os softwares, essa preocupação também precisa existir, principalmente porque eles estão cada vez mais presentes em atividades essenciais, como serviços bancários, hospitais, transportes e sistemas de comunicação. Uma falha aparentemente pequena pode provocar prejuízos financeiros, exposição de dados ou até comprometer o funcionamento de serviços importantes.

Por isso, considero que a Engenharia de Software se torna cada vez mais necessária à medida que a tecnologia passa a fazer parte de praticamente todos os aspectos da sociedade. Não basta desenvolver soluções que funcionem inicialmente; é fundamental garantir que elas continuem funcionando de maneira adequada, segura e confiável ao longo do tempo. Dessa forma, a Engenharia de Software contribui para que o desenvolvimento de sistemas deixe de ser apenas uma atividade de programação e passe a envolver um conjunto de práticas e responsabilidades voltadas à criação de soluções de qualidade.

---

## 📚 Atividade 2

### ENUNCIADO

> Programming Over Time We propose that “software engineering” encompasses not just the act of writing code, but all of the tools and processes an organization uses to build and maintain that code over time. What practices can a software organization introduce that will best keep its code valuable over the long term? How can engineers make a codebase more sustainable and the software engineering discipline itself more rigorous? We don’t have fundamental answers to these questions, but we hope that Google’s collective experience over the past two decades illuminates possible paths toward finding those answers. One key insight we share in this book is that software engineering can be thought of as “programming integrated over time.” What practices can we introduce to our code to make it sustainable—able to react to necessary change—over its life cycle, from conception to introduction to maintenance to deprecation? The book emphasizes three fundamental principles that we feel software organizations should keep in mind when designing, architecting, and writing their code:

> **Time and Change:** How code will need to adapt over the length of its life
>
> **Scale and Growth:** How an organization will need to adapt as it evolves
>
> **Trade-offs and Costs:** How an organization makes decisions, based on the lessons of Time and Change and Scale and Growth

### RESPOSTA

Um software precisa ser desenvolvido considerando todo o seu ciclo de vida, e não apenas o momento em que seu código é criado. Acredito que a ideia de compreender a Engenharia de Software como uma programação integrada ao longo do tempo seja importante, pois um código que funciona corretamente no momento de sua criação também precisa estar preparado para possíveis mudanças, correções e atualizações. Afinal, as necessidades dos usuários e das organizações podem mudar, e um sistema que não acompanha essas transformações pode se tornar ultrapassado ou até deixar de atender aos objetivos para os quais foi desenvolvido.

Os três princípios apresentados no texto ajudam a compreender melhor essa questão. O primeiro, Time and Change, destaca a importância de desenvolver códigos que possam ser modificados e adaptados ao longo do tempo, sem que cada alteração represente um grande risco para o funcionamento do sistema. Para isso, práticas como documentação, testes frequentes e organização do código são fundamentais, pois facilitam a identificação de problemas e permitem que outros desenvolvedores compreendam e deem continuidade ao trabalho.

O segundo princípio, Scale and Growth, está relacionado à capacidade de adaptação de uma organização conforme ela cresce. Um software desenvolvido para atender a uma pequena quantidade de usuários, por exemplo, pode precisar de mudanças em sua estrutura quando passar a atender milhares de pessoas. Nesse cenário, é importante considerar a escalabilidade do sistema e a organização da equipe de desenvolvimento, garantindo que o crescimento não comprometa a qualidade e o desempenho da solução.

Já o terceiro princípio, Trade-offs and Costs, demonstra que as decisões tomadas durante o desenvolvimento envolvem vantagens e desvantagens que precisam ser avaliadas. Nem sempre existe uma escolha que apresente apenas benefícios, por isso é necessário considerar as necessidades do projeto e os recursos disponíveis. Dessa forma, é importante avaliar os custos e as consequências de cada decisão, considerando não apenas os resultados imediatos, mas também os possíveis impactos que poderão surgir ao longo do tempo.

Dessa forma, considero que a sustentabilidade de um software depende tanto da qualidade do código quanto das decisões e práticas adotadas durante seu desenvolvimento. A utilização de testes, documentação, revisões de código e planejamento de atualizações contribui para tornar um sistema mais organizado e preparado para mudanças. Portanto, desenvolver um software sustentável significa pensar não somente em sua entrega, mas também em como ele será mantido, aprimorado e utilizado ao longo de sua existência.

## 📚 Atividade 3

### ENUNCIADO
> Citar e explicar 3 exemplos de tradeoffs em software

### RESPOSTA
Durante o desenvolvimento de um software, é comum que os profissionais precisem tomar decisões que envolvem vantagens e desvantagens. Essas situações são chamadas de trade-offs e acontecem quando, ao escolher determinada solução, é necessário abrir mão de algum benefício ou aceitar uma limitação em troca de outra vantagem.

Um primeiro exemplo é a escolha entre **Linux e Windows.** O Linux oferece maior liberdade de personalização e controle sobre o ambiente, mas pode exigir conhecimentos técnicos mais específicos. Já o Windows apresenta maior familiaridade para muitos usuários e compatibilidade com diversos programas, mas pode envolver custos de licenciamento. A escolha depende das necessidades do projeto e dos conhecimentos da equipe.

Outro exemplo é a utilização de **servidores próprios ou serviços em nuvem.** Os servidores próprios oferecem maior controle sobre a infraestrutura, porém exigem investimentos em equipamentos, manutenção e gerenciamento. Já a computação em nuvem oferece maior flexibilidade e facilidade de expansão, mas gera custos recorrentes e pode criar dependência do fornecedor.

Um terceiro exemplo está relacionado à **segurança e à praticidade**. Métodos de autenticação mais rigorosos, como a autenticação em dois fatores, aumentam a proteção das contas, mas tornam o acesso um pouco mais demorado. Por outro lado, métodos mais simples facilitam a utilização do sistema, mas podem oferecer menos segurança.

Esses exemplos demonstram que não existe uma solução que seja sempre a melhor em todas as situações. Por isso, é importante avaliar as vantagens, desvantagens e os custos envolvidos em cada decisão, considerando as necessidades do projeto e seus possíveis impactos futuros. Assim, os trade-offs permitem escolhas mais conscientes e contribuem para a qualidade e a sustentabilidade do software.
