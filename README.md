# index.CSS
@import url('https://fonts.googleapis.com/css2?family=Poppins&family=Roboto:wght@300&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Montserrat&display=swap');

*{
    margin: 0;
    padding: 0;
}

nav .logo {
font-family: 'Poppins', sans-serif;
align-self: center;
}

h4 {
    font-size: 2em;
}

nav {
    display: flex;
    border-bottom: 2px solid black;
    justify-content: space-between;
    padding: 20px;
    text-align: center;
    width: 100%;
}

nav ul {
    display: flex;
    list-style: none;
    font-size: 1.2em;
    justify-content: center;
    font-family: 'Montserrat', sans-serif;
}

nav ul li a{
    text-decoration: none;
    color: black;
}

nav li {
    cursor: pointer;
    transition: .3s;
    border: 1px solid black;
    padding: 15px;
    border-radius: 20px;
    margin: 5px;

}
nav li:hover {
    background-color: rgb(187, 187, 187);
}

/* ukuran mobile */
@media only screen and (max-width :600px){
    nav {
        flex-direction: column;
        align-items: center;
    }
    ul {
        flex-direction: column;
        width: 100%;
    }
}

.judul {
    width: 50%;
    margin: 55px auto;
    padding: 100px;
    text-align: center;
    font-family: 'Montserrat';
}

div p {
    font-size: 1.5em;
    color:rgb(175, 174, 174);
}

.container {
    width: 100% ;
    display: flex; 
    justify-content: space-around;
}

.thumbnail {
    text-align: center;
    margin: 5px;
    padding: 3px;
}

.thumbnail img {
    margin-bottom: 20px;
    border-radius: 10px;
    width: 100%;
    
}

.thumbnail .user {
    align-items: center;
    display: flex;
    align-content: center;
    margin-top: 60px;
    width: 50% auto;
    height: 80px;
    box-sizing: border-box;
    text-align:justify;
    justify-content: center;
    font-size: 2.5em;
    margin-bottom: 30px;
}

.thumbnail .user .label {
    margin-left: 30px;
}

.thumbnail .user p{
    margin-top: 3px;
    font-size: 0.5em;
}

.thumbnail .caption-1 {
    width: 780px;
    margin-top: 80px;
    text-align:left;
    font-family: 'Montserrat';
}

.thumbnail .benefit {
    margin-top: 50px;
    align-items: baseline;
    width: 70%;
    text-align: left;
    font-size: 1.2em;
}

.thumbnail .benefit .number-one{
    display: flex;
    align-items: baseline;
}

.thumbnail .benefit .number-one p{
    margin-left: 30px;
    font-size: 1.4em;
}

.thumbnail .benefit .number-two{
    display: flex;
    align-items: baseline;
}

.thumbnail .benefit .number-two p{
    margin-left: 30px;
    font-size: 1.4em;
}

.thumbnail .benefit .number-three{
    display: flex;
    align-items: baseline;
}

.thumbnail .benefit .number-three p{
    margin-left: 30px;
    font-size: 1.4em;
}

form {
    background-color: rgb(234, 244, 244);
    font-family: 'Montserrat';
    width: 30% auto;
    height: 70vh;
    border-radius: 10px;
    padding: 50px;
    margin: 5px;
    justify-content: center;
}

form p {
    font-size: 1.2em;
}

form input{
    display: block;
    outline: none;
    width: 100%;
    border-radius: 10px;
    height: 30px;
    border: none;
    background: white;
    border: 1px solid black;
    text-align: center;
    font-size: 14px;
}

form label{
    display: inline-block;
    margin-bottom: 7px;
    font-size: 15px;
}

form select {
    display: block;
    outline: none;
    width: 100%;
    border-radius: 10px;
    height: 30px;
    border: none;
    background: white;
    border: 1px solid black;
    text-align: center;
    font-size: 14px;
}

.btn-login{
    width: 100%;
    padding: 7px;
    border: none;
    border-radius: 10px;
    font-size: 17px;
    cursor: pointer;
    background-color: white;
    transition: .3s;
}
.btn-login:hover{
    background-color:slategrey;
}
