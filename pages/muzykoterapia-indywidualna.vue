<template>
  <div class="event">
    <div class="main">
      <div class="wrapper">
        <div class="content">
          <div class="title">
            MUZYKORERAPIA INDYWIDUALNA dla osób każdym wieku
          </div>
          <div class="text">
            Muzykoterapia to usystematyzowany proces terapii, który wykorzystuje muzykę i jej elementy dla ułatwienia
            komunikacji, uczenia się mobilizacji, ekspresji, koncentracji, poprawy sfery fizycznej, emocjonalnej,
            intelektualnej oraz poznawczej w celu rozwoju wewnętrznego potencjału uczestnika terapii. Dysponuje wieloma
            metodami, technikami muzykoterapeutycznymi, dzięki którym terapeuta dostosowuje się do potrzeb terapeutycznych
            danego uczestnika.
          </div>
          <div class="button-wrapper">
            <Button label="Zapisz się" />
          </div>
        </div>
        <div class="photo">
          <BubblePhoto img="guitar.jpg" />
        </div>
      </div>
    </div>
    <div class="wrapper">

      <div class="sign">
        <div class="text">
          <div class="title">
            MUZYKORERAPIA INDYWIDUALNA dla osób każdym wieku
          </div>
          <div class="info">
            <div class="col">
              <div class="row">
                <div class="label">Termin</div>
                <div class="value">
                  <div>PONIEDZIAŁKI 15.00</div>
                  <div>ŚRODY 14.00, 19.00</div>
                  <div>CZWARTKI 16.15</div>
                  <div>PIĄTKI 16.00</div>
                </div>
              </div>
            </div>
            <div class="col">
              <div class="row">
                <div class="label">KOSZT</div>
                <div class="value">
                  <div>
                    45 MINUT 120 ZŁ
                  </div>
                  <div>
                    60 MINUT 140 ZŁ
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="note">
          <NotesIcon />
        </div>
        <div class="button-wrapper">
          <Button label="zapisze się!" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import BrainIcon from '../components/icons/BrainIcon.vue';
import UsersIcon from '../components/icons/UsersIcon.vue';
import NotesIcon from '../components/icons/NotesIcon.vue';
import HeartIcon from '../components/icons/HeartIcon.vue';



export default {
  name: 'muzykoterapia-grupowa',
  components: { BrainIcon, HeartIcon, NotesIcon, UsersIcon }
}
</script>
