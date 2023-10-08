
<template>
  <div class="event">
    <div class="main">
      <div class="wrapper">
        <div class="content">
          <div class="title">
            RODZINNE MUZYKOWANIA w sobotę
          </div>
          <div class="text">
            Są to zajęcia muzyczne dla rodziny. Celem zajęć jest uatrakcyjnienie rodzinnego czasu w miejscu, gdzie można
            śpiewać, grać na wielu instrumentach (dużych i małych), wspólnie muzykować i dobrze się razem bawić.
          </div>
          <div class="text">
            Pragniemy, aby nasze wydarzenie miało charakter rodzinny, ponieważ zależy nam na budowaniu dobrych więzi i
            relacji rodzinnych, właśnie za pomocą muzyki.  Dlatego na zajęciach będzie tylko WASZA rodzina i najbliżsi.
            Dla dzieci jak i dla rodziców będzie to sposób na spędzenie ze sobą czasu w inny, ciekawy, twórczy sposób.
            Będzie to rozwojowe zarówno dla dziecka jak i rodzica. Zdajemy sobie sprawę, że w tygodniu jest nam trudno
            znaleźć czas dla rodziny – praca, dom, zajęcia, obowiązki. Stąd proponujemy Wam zajęcia w SOBOTY! Na zajęcia
            może przyjść max 7 osób – więc mogą to być: dzieci, rodzice, dziadkowie, babcie, dziadkowie, kuzynki, kuzyni,
            przyjaciele itd. Możecie wziąć ze sobą kogo chcecie Nie ma ograniczeń wiekowych. W tych zajęciach może wziąć
            każdy udział.
          </div>
          <div class="subtitle">
            Nie ma to jak twórcze wielopokoleniowe zajęcia!
          </div>
          <div class="button-wrapper">
            <Button label="Zapisz się" />
          </div>
        </div>
        <div class="photo">
          <BubblePhoto img="muzka_5.jpg" />
        </div>
      </div>
    </div>
    <div class="wrapper">
      <div class="list">
        <div class="title">
          NA ZAJĘCIACH BĘDZIEMY:
        </div>
        <ul>
          <li>
            <span>uczestniczyć w różnych doświadczeniach muzycznych, które nas rozluźnia i wprawią w nas dobry
              humor!
            </span>
          </li>
          <li>
            <span>poznawać różne instrumenty, na których wszyscy członkowie rodziny będą mogli wspólnie grać</span>
          </li>
          <li>
            <span>nieco się ruszać przy muzyce</span>
          </li>
          <li>
            <span>uczestniczyć w różnych doświadczeniach muzycznych, które nas rozluźnia i wprawią w nas dobry
              humor!</span>
          </li>
        </ul>
      </div>
      <div class="sign">
        <div class="text">
          <div class="title">
            RODZINNE MUZYKOWANIA w sobotę
          </div>
          <div class="info">
            <div class="col">
              <div class="row">
                <div class="label">Dzień</div>
                <div class="value">Sobota raz w miesiącu</div>
              </div>
              <div class="row">
                <div class="label">Godzina</div>
                <div class="value">
                  <div>10:00-11:00</div>
                  <div>11:15-12:15</div>
                  <div>12:30-13:30</div>
                </div>
              </div>
            </div>
            <div class="col">
              <div class="row">
                <div class="label">Koszt</div>
                <div class="value">130 zł</div>
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
