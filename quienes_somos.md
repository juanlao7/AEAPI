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
        <img class="circled" src="assets/img/people/paola.jpg" />
        <p>Paola Moreno Alcibar</p>
        <p>Presidenta</p>
    </div>

    <div>
        <img class="circled" src="assets/img/people/marina.jpg" />
        <p>Marina O'Neill Muñoz</p>
        <p>Secretaria</p>
    </div>

    <div>
        <img class="circled" src="assets/img/people/mary.jpg" />
        <p>Mary Jane Mollstätter</p>
        <p>Tesorera</p>
    </div>
</div>
