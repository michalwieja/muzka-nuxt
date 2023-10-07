<template>
  <div class="contact-wrapper">
    <div class="wrapper">
      <div class="contact">
        <div class="title">
          Kontakt
        </div>
        <div class="content">
          <div class="socials">
            <div class="social fb">
              <FbIcon /> <a href="https://www.facebook.com/MuzKaMuzykoterapia"
                target="_blank">facebook/MuzKaMuzykoterapia</a>
            </div>
            <div class="social ig">
              <IgIcon /> <a href="https://www.instagram.com/muzkamuzykoterapia/"
                target="_blank">instagram/muzkamuzykoterapia</a>
            </div>
            <div class="social phone">
              <PhoneIcon /> <a href="tel:+48 666 059 078">+48 666 059 078</a>
            </div>
          </div>
          <div class="data">
            <div class="social mail">
              <EmailIcon /> <a href="mailto:kontakt@muzka.katowice.pl">kontakt@muzka.katowice.pl</a>
            </div>
            <div class="social address">
              <AddressIcon />Katowice, Brzozowa 50
            </div>
          </div>
        </div>

      </div>
      <footer>
        Copyright &copy; MuzKa {{ currentDate.getFullYear() }}
        All rights reserved
      </footer>
    </div>
  </div>
</template>

<script>

import FbIcon from '../components/icons/FbIcon.vue';
import IgIcon from '../components/icons/IgIcon.vue';
import PhoneIcon from '../components/icons/PhoneIcon.vue';
import EmailIcon from '../components/icons/EmailIcon.vue';
import AddressIcon from '../components/icons/AddressIcon.vue';
export default {
  components: {
    FbIcon,
    IgIcon,
    PhoneIcon,
    EmailIcon,
    AddressIcon
  },
  name: 'Contact',
  data() {
    return {
      currentDate: new Date()
    }
  }
}
</script>
