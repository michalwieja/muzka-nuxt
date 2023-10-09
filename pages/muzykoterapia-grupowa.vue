<template>
  <div class="event">
    <div class="main">
      <div class="wrapper">
        <div class="content">
          <div class="title" data-aos="fade-in">
            MUZYKOTERAPIA GRUPOWA DLA DZIECI Z NEURO RÓŻNORODNOŚCIĄ oraz z trudnościami społecznymi
          </div>
          <div class="subtitle" data-aos="fade-in">
            Co to Muzykoterapia Grupowa dla dzieci 4-6
          </div>
          <div class="text" data-aos="fade-in">
            To działania poprzez aktywności muzyczne, które są skoncentrowane na uczestniku i na jego rozwoju. Główne
            założenia grupy opierają się na realizowaniu potrzeb uczestnika, dostrzeganiu i rozwijaniu jego zasobów,
            mocnych
            stron, za pomocą twórczych doświadczeń muzycznych.
            Muzykoterapia grupowa to działania muzyczne, które stwarzają przestrzeń do rozwoju, uczenia się nowych rzeczy
            w
            grupie, przynosząc wiele pozytywnych odczuć i emocji.
          </div>
          <div class="button-wrapper">
            <Button label="Zapisz się" />
          </div>
        </div>
        <div class="photo" data-aos="fade-in">
          <BubblePhoto img="muzka_3.jpg" />
        </div>
      </div>
    </div>
    <div class="wrapper">
      <div class="title" data-aos="fade-in">
        JAK TO WYGLĄDA I JAKI JEST CEL?
      </div>
      <div class="cards" data-aos="fade-in">
        <div class="card">
          <BrainIcon />
          <div>
            wspólne śpiewanie znanych i nieznanych piosenek wyzwala kreatywność, oryginalność
            myślenia, wspomaga rozwój poznawczy - uwagę, zapamiętywanie, rozwijanie różnych operacji myślowych, wydłuża i
            przyspiesza proces myślenia,
          </div>
        </div>
        <div class="card">
          <UsersIcon />
          <div>
            granie na instrumentach i tworzenie muzycznych zespołów - wspiera umiejętności podejmowania decyzji, radzenia
            sobie w grupie, rozwijania umiejętności współpracy z innymi, komunikowania się z innymi oraz wzajemnego
            słuchania; rozwija prawidłowe zachowania związane z kontaktem
          </div>
        </div>
        <div class="card">
          <NotesIcon />
          <div>
            tworzenie piosenek – pisanie słów piosenki i muzyki – umiejętności współpracy, ekspresji swoich myśli,
            potrzeb, emocji w słowach piosenki, w grze; stopniowe uświadamianie swoich emocji, ich nazywanie;
          </div>
        </div>
        <div class="card">
          <HeartIcon />
          <div>
            Muzykoterapia grupowa daje okazję do poznawania, rozwijania, modyfikowania różnych społecznych zachowań w
            bezpiecznej atmosferze. To taki trening umiejętności społecznych w muzycznej formie. Ponadto to dobra okazja
            do przeżywania, poznawania, identyfikowania emocji, które powstają właśnie podczas kontaktów z innymi
          </div>
        </div>
      </div>
      <div class="sign" data-aos="fade-in">
        <div class="text">
          <div class="title">
            MUZYKOTERAPIA GRUPOWA DLA DZIECI Z NEURO RÓŻNORODNOŚCIĄ oraz z trudnościami społecznymi
          </div>
          <div class="info">
            <div class="col">
              <div class="row">
                <div class="label">godzina:</div>
                <div class="value">17:15</div>
              </div>
              <div class="row">
                <div class="label">dzień:</div>
                <div class="value">środa</div>
              </div>
            </div>
            <div class="col">
              <div class="row">
                <div class="label">KOSZT: 15 ZAJĘĆ W SEMESTRZE</div>
                <div class="value">900 zł</div>
              </div>
              <div class="row">
                <div class="label">Można rozłożyć płatność na dwie raty.</div>
              </div>
            </div>
          </div>
          <div class="subtitle">
            Zajęcia odbywają się w małych grupach (max piątka dzieci)
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
