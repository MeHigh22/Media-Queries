# Exexrcice 2 -> Media Queries

## - Pour des écrans plus grands que 1024px le titre h1 a une taille de 50px 

@media screen and (max-width:1024px) {
    h1 {
        font-size:50px;
    }
}

## - Pour des écrans entre 600px et 1024px le titre h1 a une taille de 25px

@media screen and (max-width:1024px) and (min-width:600px){
h1 {
    font-size:25px;
}
}

## - Pour des écrans ntre 320px et 600px le titre h1 a une taille de 15px