https://i.pinimg.com/originals/8e/39/54/8e395469b288061b0a26b759e1109bd9.png (Ilha)
https://agendor-blog-uploads.s3.sa-east-1.amazonaws.com/2022/09/12094319/trilha-de-aprendizagem-organizacional.jpg (trilha escolha A)
https://media.istockphoto.com/id/153752095/pt/foto/selva-profunda.jpg?s=612x612&w=0&k=20&c=mQ4rxWzjNnzJWrDXMj93LJyz47ydOvyNJrhc3kl-gnI= (escolha B)
https://curlytales.com/wp-content/uploads/2022/11/The-Longest-Bridge.jpg (Escolha C)
https://media.istockphoto.com/id/459861239/pt/foto/rio-ao-p%C3%B4r-do-sol-de-ver%C3%A3o.jpg?s=612x612&w=0&k=20&c=-1IufW2jGr1bjL7_cAuSfTRmKNi4YCWUpKc5YqkogQc= (escolha D)
https://www.shutterstock.com/image-photo/entrance-old-abandoned-limestone-adits-600nw-2280577421.jpg (escolha E)
https://media.istockphoto.com/id/1346756949/photo/natural-pattern-of-pine-tree-trunks-in-a-dense-forest.jpg?s=612x612&w=0&k=20&c=diAQQvLm74ONQURVe2UyB7euQphP49XhvLCHy2tSw_M= (Escolha F)

FINAL 1: https://media.npr.org/assets/img/2020/06/08/fenn002_custom-28fd8c06a224983d8ad75ea6d7338dab99cc77b2.jpg
FINAL 2: https://www.thedailygardener.com/wp-content/uploads/2021/12/Pit-Trap.jpeg
FINAL 3: https://t3.ftcdn.net/jpg/01/21/80/16/360_F_121801600_CMAfgueYYBiq0w88E1r5Lkklp7Hl1AO4.jpg
FINAL 4: https://parade.com/.image/t_share/MTkwNTc4Mzg4MDIzNzE0OTQx/lost-wilderness-ftr.jpg

/* Estilo básico do corpo */
body {
    background-color: #f4f4f9;
    font-family: 'Arial', sans-serif;
    color: #333;
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    overflow: hidden;
}

/* Container principal do jogo */
#game {
    background-color: #fff;
    border: 2px solid #ccc;
    border-radius: 10px;
    width: 90%;
    max-width: 800px;
    padding: 20px;
    text-align: center;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

/* Título do jogo */
#title {
    font-size: 24px;
    font-weight: bold;
    margin-bottom: 20px;
    color: #2c3e50;
}

/* Imagem da cena */
#scene-image {
    width: 100%;
    max-height: 400px;
    object-fit: cover;
    border-radius: 5px;
    margin-bottom: 20px;
}

/* Texto da história */
#story {
    font-size: 18px;
    line-height: 1.6;
    margin-bottom: 20px;
    color: #34495e;
}

/* Container dos botões de escolha */
#choices {
    display: flex;
    flex-direction: column;
    gap: 10px;
}

/* Estilo dos botões */
button {
    padding: 10px 20px;
    font-size: 16px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    transition: background-color 0.3s, transform 0.2s;
    color: #fff;
}

/* Estilo de botões padrão */
button:nth-child(1) {
    background-color: #3498db;
}

button:nth-child(2) {
    background-color: #e67e22;
}

/* Efeito de hover nos botões */
button:hover {
    background-color: #2ecc71;
    transform: scale(1.05);
}

/* Responsividade para telas menores */
@media (max-width: 600px) {
    #game {
        width: 95%;
        padding: 15px;
    }

    #title {
        font-size: 20px;
    }

    #story {
        font-size: 16px;
    }

    button {
        font-size: 14px;
        padding: 8px 16px;
    }
}
