
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f4f7f8;
    color: #333;
    line-height: 1.6;
}

header {
    background-color: #123b52;
    color: white;
    padding: 20px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
}

nav a {
    color: white;
    text-decoration: none;
    margin: 10px;
    font-weight: bold;
}

nav a:hover {
    color: #ffd166;
}

.hero {
    background: linear-gradient(135deg, #123b52, #219ebc);
    color: white;
    text-align: center;
    padding: 100px 20px;
}

.hero h2 {
    font-size: 40px;
    margin-bottom: 15px;
}

.hero p {
    margin-bottom: 25px;
}

.btn {
    background-color: #ffd166;
    color: #123b52;
    text-decoration: none;
    padding: 12px 25px;
    border-radius: 5px;
    font-weight: bold;
}

.btn:hover {
    background-color: white;
}

#destinations {
    padding: 50px 20px;
    text-align: center;
}

#destinations h2,
#contact h2 {
    margin-bottom: 25px;
    color: #123b52;
}

.cards {
    display: flex;
    justify-content: center;
    gap: 20px;
    flex-wrap: wrap;
}

.card {
    background-color: white;
    padding: 30px 20px;
    width: 280px;
    border-radius: 10px;
    box-shadow: 0 4px 10px #00000015;
}

.card h3 {
    color: #219ebc;
    margin-bottom: 10px;
}

#contact {
    background-color: #e3f2f5;
    text-align: center;
    padding: 50px 20px;
}

footer {
    background-color: #123b52;
    color: white;
    text-align: center;
    padding: 15px;
}

@media (max-width: 600px) {
    header {
        flex-direction: column;
        gap: 15px;
    }

    .hero h2 {
        font-size: 30px;
    }

    .card {
        width: 100%;
        max-width: 350px;
    }
}
