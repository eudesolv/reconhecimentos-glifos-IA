<h1> Grimório de Visão Computacional </h1>

<p> Projeto da matéria de Inteligência Artificial, desenvolvido com Python utilizando a biblioteca OpenCV/Numpy e TensorFlow para o reconhecimento dos glifos mágicos através de classificação de imagens com o Teachable Machine </p>

<p align = "center">
<img width="480" height="270" alt="Image" src="https://github.com/user-attachments/assets/45af37e4-08ad-457b-a58f-71cc87a91840" />
</p>


<h2> Sobre o nosso Projeto </h2>
<p> O sistema funciona como um grimório interativo. O programa processa a imagem de um glifo elemental (Fogo, Água, Luz, Vento ou Planta), utiliza um modelo preditivo treinado para identificar qual elemento foi apresentado, e dispara a animação mágica correspondente na tela. </p>

<h2> Tecnologias Utilizadas </h2>
<ul>
 <li> <strong> Python </strong> </li>
 <li> <strong> OpenCV </strong> </li>
 <li> <strong> TensorFlow / Keras </strong> </li>
 <li> <strong> Numpy </strong> </li>
  
</ul>

<h2> Estrutura do Repositório</h2>
    <pre><code>reconhecimento-glifos-IA/
├── modelo/
│   ├── keras_model.h5      # Cérebro treinado da IA
│   └── labels.txt          # Classes (Fogo, Gelo, Luz, Planta, Vazio)
├── videos/                 # Animações de magia correspondentes
├── main.py                 # Script principal da aplicação
└── README.md               # Documentação do projeto</code></pre>

<h2> Como Executar o Projeto </h2>
<ol>
        <li>
            <strong>Clone o repositório:</strong>
            <pre><code>git clone https://github.com/Anton-Gabriel-code/reconhecimento-glifos-IA.git
cd reconhecimento-glifos-IA</code></pre>
        </li>
        <li>
            <strong>Instale as dependências necessárias:</strong>
            <pre><code>pip install tensorflow opencv-python numpy</code></pre>
        </li>
        <li>
            <strong>Execute o script principal:</strong>
            <pre><code>python main.py</code></pre>
        </li>
    </ol>



 <h4>Alunos: Antônio Gabriel e Eudes Oliveira</h4>


