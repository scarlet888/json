const cardData = {
    card: {
        image: {
            src: "https://raw.githubusercontent.com/scarlet1837/images/refs/heads/main/IMG_6123.webp",
            alt: "Esign HDFC Life"
        },
        content: {
            title: "esign",
            description: "Cert : China CITIC Bank Corporation Limited"
        },
        downloadLink: {
            href: "https://tinyurl.com/fk9zb8kh"
        }
    }
};

function renderCard(data) {
    // Create elements
    const cardElement = document.createElement('div');
    cardElement.className = 'card';

    const imgElement = document.createElement('img');
    imgElement.src = data.card.image.src;
    imgElement.alt = data.card.image.alt;

    const contentElement = document.createElement('div');
    contentElement.className = 'content';

    const titleElement = document.createElement('h2');
    titleElement.innerText = data.card.content.title;

    const descriptionElement = document.createElement('p');
    descriptionElement.innerText = data.card.content.description;

    const downloadLink = document.createElement('a');
    downloadLink.href = data.card.downloadLink.href;
    downloadLink.className = 'download-icon';
    downloadLink.innerText = "Download"; 

    contentElement.appendChild(titleElement);
    contentElement.appendChild(descriptionElement);
    cardElement.appendChild(imgElement);
    cardElement.appendChild(contentElement);
    cardElement.appendChild(downloadLink);

    document.body.appendChild(cardElement);
}

renderCard(cardData);
