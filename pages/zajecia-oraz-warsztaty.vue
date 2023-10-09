
<template>
  <div class="event">
    <div class="main">
      <div class="wrapper">
        <div class="content">
          <div class="title" data-aos="fade-in">
            MUZKOLAKI Starszaki
          </div>
          <div class="text" data-aos="fade-in">
            Muzkolaki Starszaki - Muzyczna Zabawa dla Dzieci - to zajęcia muzyczno-ruchowe z elementami muzykoterapii.
            Zajęcia mają przede wszystkim wspierać dziecko w rozwoju dając mu przestrzeń na swobodne, twórcze działania.
            Zapewniamy dużą dawkę muzycznej ekspresji, śpiewania, grania na wielu instrumentach, duuuuużo muzycznych
            niespodzianek i wiele zabawy dla dziecka jak i rodzica/opiekuna. Rozwijamy sferę społeczną, poznawczą oraz
            emocjonalną Twojego dziecka za pomocą odpowiednich działań muzycznych. To czas kontaktu z żywą muzyką, gdzie
            dziecko może samo po dotykać, po eksplorować, poczuć, zobaczyć i przeżyć. To działania muzyczne, w których
            prowadzący nie stara się kontrolować dziecka ani zmieniać jego działań, ale za pomocą zabawy muzycznej i
            nawiązywania dzięki niej relacji, stwarzać każdemu dziecku przestrzeń do rozwoju.
            Wszelkie działania są dostosowane do dziecka, jego potrzeb i wieku. 
          </div>
          <div class="button-wrapper">
            <Button label="Zapisz się" />
          </div>
        </div>
        <div class="photo" data-aos="fade-in">
          <BubblePhoto img="guitar_2.jpg" />
        </div>
      </div>
    </div>
    <div class="wrapper">
      <div class="sign" data-aos="fade-in">
        <div class="text">
          <div class="title">
            MUZKOLAKI Starszaki
          </div>
          <div class="info">
            <div class="col">
              <div class="row">
                <div class="label">godzina:</div>
                <div class="value">17:00</div>
              </div>
              <div class="row">
                <div class="label">dzień:</div>
                <div class="value">poniedziałek</div>
              </div>
            </div>
            <div class="col">
              <div class="row">
                <div class="label">KOSZT: JEDNE ZAJĘCIA</div>
                <div class="value">55 zł</div>
              </div>
              <div class="row">
                <div class="label">4 zajęcia wazne 5 tygodni</div>
                <div class="value">200 zł</div>
              </div>
            </div>
          </div>
          <div class="subtitle">
            Płatności dokonywane są przed zajęciami.
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
      <div class="additional">
        <div class="title" data-aos="fade-in">WARSZTATY INSTRUMENTALNE DLA DZIECI 7-9 lat
          ŚRODY O 18.15 CO DWA TYGODNIE
        </div>
        <div class="text" data-aos="fade-in">
          Muzyka ma w sobie bardzo duży potencjał społeczny i emocjonalny. Jak pisze norweski muzykoterapeuta Even Ruud;
          „bycie zaangażowanym w muzykę oznacza silniejsze poczucie tożsamości i stopniowe dążenie do poprawy swojej
          jakości
          życia”. Taką zasadą będziemy się kierować w ramach naszych warsztatów „Siła muzyki w grupie”.
          Warsztat jest muzyczną przestrzenią dla tych, którzy za pomocą swojego głosu, ciała, ruchu, gry na wielu
          instrumentach chcą wspólnie pomuzykować z innymi ludźmi. Chcą poznać ich za pomocą muzycznego kanału.
          Będzie to czas niesamowity bo spędzony z różnymi osobami, mającymi inne doświadczenia, przeżycia, potrzeby.
          Pomimo
          tych różnic i nieznajomości siebie będziemy starali się stworzyć coś wspólnego, coś muzycznego w bezpiecznej
          atmosferze, zgodnie z zasadą „angażuje się na tyle na ile chcę i potrzebuję”. Osoby chcące wziąć udział w
          warsztatach nie muszą posiadać żadnych umiejętności muzycznych, by współtworzyć muzyczny świat. Dlatego do
          udziału
          zachęcamy wszystkich!
          Warsztat składa się z dwóch części:
          ♫ cześć 1 – integracja grupy, działania wprowadzające, rozgrzewające. Będziemy poznawać siebie poprzez różne
          muzyczne formy aktywności.
          ♫ cześć 2 – działania z improwizacją, z piosenką – tutaj będziemy zmierzać do wyrażenia siebie poprzez muzykę,
          znalezienie swojego miejsca w grupie oraz dostrzeżenie potencjału każdego członka grupy jako jednostki
          niezastąpionej.
        </div>
        <div class="button-wrapper" data-aos="fade-in">
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
