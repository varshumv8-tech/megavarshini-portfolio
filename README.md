*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    font-family:Arial,sans-serif;
    line-height:1.6;
    background:#f5f7fa;
    color:#222;
}

.skip-link{
    position:absolute;
    left:-9999px;
}

.skip-link:focus{
    left:10px;
    top:10px;
    background:#000;
    color:#fff;
    padding:10px;
}

header{
    background:#1e3a8a;
    color:white;
    text-align:center;
    padding:20px;
}

nav ul{
    list-style:none;
    display:flex;
    justify-content:center;
    gap:20px;
    margin-top:15px;
    flex-wrap:wrap;
}

nav a{
    color:white;
    text-decoration:none;
    font-weight:bold;
}

nav a:hover,
nav a:focus{
    text-decoration:underline;
}

main{
    max-width:1000px;
    margin:auto;
    padding:30px;
}

section{
    margin-bottom:30px;
}

.profile-image{
    width:200px;
    border-radius:50%;
    margin:20px 0;
}

.card{
    background:white;
    padding:20px;
    margin-bottom:20px;
    border-radius:10px;
    box-shadow:0 2px 6px rgba(0,0,0,0.1);
}

form{
    display:flex;
    flex-direction:column;
}

label{
    margin-top:10px;
}

input,
textarea{
    padding:10px;
    margin-top:5px;
}

button{
    margin-top:15px;
    padding:12px;
    background:#1e3a8a;
    color:white;
    border:none;
    cursor:pointer;
}

button:hover,
button:focus{
    opacity:0.9;
}

footer{
    text-align:center;
    background:#1e3a8a;
    color:white;
    padding:15px;
    margin-top:20px;
}

@media(max-width:768px){
    nav ul{
        flex-direction:column;
    }
}
