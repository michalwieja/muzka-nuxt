
<template>
  <div class="event">
    <div class="main">
      <div class="wrapper">
        <div class="content">
          <div class="title" data-aos="fade-in">
            MUZYCZNY KRĄG KOBIET
          </div>
          <div class="text" data-aos="fade-in">
            W natłoku codziennych spraw, stresującej pracy, licznych obowiązków i myślenia o innych, nadchodzi moment
            zmęczenia, przeciążenia. Coraz rzadziej doświadczamy wtedy radości i lekkości, a dominują nad nami ciemne
            myśli, niezadowolenie, napięcie w ciele, czasem ból. Odczucia te blokują nas, nasze działanie. Chroniczne
            napięcie sprawia, że pogarsza się nasz stan psychofizyczny, nie potrafimy wziąć pełnego oddechu, powoli
            zatracamy siebie…
            To czego potrzebujemy to być może odpoczynku i relaksu, czasu dla siebie, swojego ciała i potrzeb. Czasu i
            przestrzeni, aby zaopiekować się sobą i wrócić do siebie. Wtedy dopiero możemy sięgnąć do naszego
            wewnętrznego potencjału kobiety. Taką właśnie okazję może dostarczyć Muzyczny Krąg Kobiet.
          </div>
          <div class="button-wrapper" data-aos="fade-in">
            <Button label="Zapisz się" />
          </div>
        </div>
        <div class="photo" data-aos="fade-in">
          <BubblePhoto img="muzka_4.jpg" />
        </div>
      </div>
    </div>
    <div class="wrapper">
      <div class="sign" data-aos="fade-in">
        <div class="text">
          <div class="title">
            MUZYCZNY KRĄG KOBIET
          </div>
          <div class="info">
            <div class="col">
              <div class="row">
                <div class="label">Grupa ma charakter otwarty.</div>
              </div>
              <div class="row">
                <div class="label">Każda dziewczyna, kobieta może dołączyć</div>
              </div>
              <div class="row">
                <div class="value">OBOWIĄZUJĄ ZAPISY</div>
              </div>
              <div class="row">
                <div class="label">Koszt od osoby:</div>
                <div class="value">100 zł</div>
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
