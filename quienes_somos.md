<style>
    #backgroundImage {
        background-image: url('assets/img/background_2.jpg');
    }

    #content {
        padding-left: 0;
        padding-right: 0;
        text-align: center;
    }

    #content h1 {
        margin-bottom: 2em;
    }

    #people div {
        width: 49%;
        display: inline-block;
        padding: 0 10% 5%;
        box-sizing: border-box;
        vertical-align: top;
    }

    #people div p {
        text-align: center;
        margin: 1em;
    }

    #people div img + p {
        font-weight: bold;
    }

    @media screen and (max-width: 570px) {
        #people div p {
            font-size: 3vw;
        }
    }
</style>

# Nuestro equipo

<div id="people">
    <div>
        <img class="circled" src="assets/img/people/cersei_lannister.jpg" />
        <p>Cersei Lannister</p>
        <p>Reina consorte de los Siete Reinos</p>
    </div>

    <div>
        <img class="circled" src="assets/img/people/daenerys_targaryen.jpg" />
        <p>Daenerys Targaryen</p>
        <p>Heredera al Trono de Hierro</p>
    </div>

    <div>
        <img class="circled" src="assets/img/people/sansa_stark.jpg" />
        <p>Sansa Stark</p>
        <p>Señora de Invernalia</p>
    </div>

    <div>
        <img class="circled" src="assets/img/people/arya_stark.jpg" />
        <p>Arya Stark</p>
        <p>Paralegal</p>
    </div>
</div>
