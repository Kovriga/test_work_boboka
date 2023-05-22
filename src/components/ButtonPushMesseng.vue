<template>
  <div class="main">
    <div class="btn-main">
      <div class="btn-push-message" @click="updateTime">
        <svg width="10" height="20" viewBox="0 0 10 20" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path fill-rule="evenodd" clip-rule="evenodd"
                d="M9.73828 19.6712C10.0971 19.2446 10.0855 18.5664 9.71229 18.1562L2.2901 10L9.71229 1.84375C10.0855 1.43361 10.0971 0.755356 9.73828 0.328814C9.37941 -0.0977268 8.78593 -0.111027 8.41271 0.299108L0.28771 9.22768C0.103886 9.42968 -5.03821e-07 9.70855 -5.1656e-07 10C-5.293e-07 10.2914 0.103886 10.5703 0.28771 10.7723L8.41271 19.7009C8.78593 20.111 9.37941 20.0977 9.73828 19.6712Z"
                fill="white"/>
        </svg>
        <p>Отправить сообщение</p>
        <span class="time-action-btn">
      </span>
      </div>
      <div class="btn-push-message time-action-btn-disable" @click="updateTime">
        <p id="text-box"></p>
        <span class="time-action-btn">
        <span id="rocket"></span>
      </span>
      </div>
      <div class="btn-push-message" @click="updateTime">
        <p>Отправить сообщение</p>
        <svg width="10" height="20" viewBox="0 0 10 20" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path fill-rule="evenodd" clip-rule="evenodd"
                d="M0.26172 19.6712C-0.0971487 19.2446 -0.0855119 18.5664 0.287712 18.1562L7.7099 10L0.287711 1.84375C-0.0855127 1.43361 -0.0971495 0.755356 0.261719 0.328814C0.620588 -0.0977268 1.21407 -0.111027 1.58729 0.299108L9.71229 9.22768C9.89611 9.42968 10 9.70855 10 10C10 10.2914 9.89611 10.5703 9.71229 10.7723L1.58729 19.7009C1.21407 20.111 0.620589 20.0977 0.26172 19.6712Z"
                fill="#FAFAFA"/>
        </svg>
        <span class="time-action-btn">
      </span>
      </div>
    </div>
    <p>Не помню пароль</p>
    <div class="btn-svg">
      <div class="btn-svg-form-end-color little">
        <svg width="40%" height="40%" viewBox="0 0 12 12" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path fill-rule="evenodd" clip-rule="evenodd"
                d="M1.09743 0.188289C0.846374 -0.0627628 0.43934 -0.0627628 0.188289 0.188289C-0.0627628 0.43934 -0.0627628 0.846374 0.188289 1.09743L5.09086 6L0.188289 10.9026C-0.0627628 11.1536 -0.0627628 11.5607 0.188289 11.8117C0.43934 12.0628 0.846374 12.0628 1.09743 11.8117L6 6.90914L10.9026 11.8117C11.1536 12.0628 11.5607 12.0628 11.8117 11.8117C12.0628 11.5607 12.0628 11.1536 11.8117 10.9026L6.90914 6L11.8117 1.09743C12.0628 0.846374 12.0628 0.43934 11.8117 0.188289C11.5607 -0.0627628 11.1536 -0.0627628 10.9026 0.188289L6 5.09086L1.09743 0.188289Z"
                fill="#FAFAFA"/>
        </svg>
      </div>
      <div class="btn-svg-form-end-color">
        <svg width="40%" height="40%" viewBox="0 0 12 12" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path fill-rule="evenodd" clip-rule="evenodd"
                d="M1.09743 0.188289C0.846374 -0.0627628 0.43934 -0.0627628 0.188289 0.188289C-0.0627628 0.43934 -0.0627628 0.846374 0.188289 1.09743L5.09086 6L0.188289 10.9026C-0.0627628 11.1536 -0.0627628 11.5607 0.188289 11.8117C0.43934 12.0628 0.846374 12.0628 1.09743 11.8117L6 6.90914L10.9026 11.8117C11.1536 12.0628 11.5607 12.0628 11.8117 11.8117C12.0628 11.5607 12.0628 11.1536 11.8117 10.9026L6.90914 6L11.8117 1.09743C12.0628 0.846374 12.0628 0.43934 11.8117 0.188289C11.5607 -0.0627628 11.1536 -0.0627628 10.9026 0.188289L6 5.09086L1.09743 0.188289Z"
                fill="#FAFAFA"/>
        </svg>
      </div>
      <div class="btn-svg-form-end-color little">
        <svg width="40%" height="40%" viewBox="0 0 10 20" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path fill-rule="evenodd" clip-rule="evenodd"
                d="M9.73828 19.6712C10.0971 19.2446 10.0855 18.5664 9.71229 18.1562L2.2901 10L9.71229 1.84375C10.0855 1.43361 10.0971 0.755356 9.73828 0.328814C9.37941 -0.0977268 8.78593 -0.111027 8.41271 0.299108L0.28771 9.22768C0.103886 9.42968 -5.03821e-07 9.70855 -5.1656e-07 10C-5.293e-07 10.2914 0.103886 10.5703 0.28771 10.7723L8.41271 19.7009C8.78593 20.111 9.37941 20.0977 9.73828 19.6712Z"
                fill="white"/>
        </svg>
      </div>
      <div class="btn-svg-form-end-color">
        <svg width="40%" height="40%" viewBox="0 0 10 20" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path fill-rule="evenodd" clip-rule="evenodd"
                d="M9.73828 19.6712C10.0971 19.2446 10.0855 18.5664 9.71229 18.1562L2.2901 10L9.71229 1.84375C10.0855 1.43361 10.0971 0.755356 9.73828 0.328814C9.37941 -0.0977268 8.78593 -0.111027 8.41271 0.299108L0.28771 9.22768C0.103886 9.42968 -5.03821e-07 9.70855 -5.1656e-07 10C-5.293e-07 10.2914 0.103886 10.5703 0.28771 10.7723L8.41271 19.7009C8.78593 20.111 9.37941 20.0977 9.73828 19.6712Z"
                fill="white"/>
        </svg>
      </div>
      <div class="btn-svg-form-end-color little">
        <svg width="40%" height="40%" viewBox="0 0 10 20" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path fill-rule="evenodd" clip-rule="evenodd"
                d="M0.26172 19.6712C-0.0971487 19.2446 -0.0855119 18.5664 0.287712 18.1562L7.7099 10L0.287711 1.84375C-0.0855127 1.43361 -0.0971495 0.755356 0.261719 0.328814C0.620588 -0.0977268 1.21407 -0.111027 1.58729 0.299108L9.71229 9.22768C9.89611 9.42968 10 9.70855 10 10C10 10.2914 9.89611 10.5703 9.71229 10.7723L1.58729 19.7009C1.21407 20.111 0.620589 20.0977 0.26172 19.6712Z"
                fill="#FAFAFA"/>
        </svg>
      </div>
      <div class="btn-svg-form-end-color ">
        <svg width="40%" height="40%" viewBox="0 0 10 20" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path fill-rule="evenodd" clip-rule="evenodd"
                d="M0.26172 19.6712C-0.0971487 19.2446 -0.0855119 18.5664 0.287712 18.1562L7.7099 10L0.287711 1.84375C-0.0855127 1.43361 -0.0971495 0.755356 0.261719 0.328814C0.620588 -0.0977268 1.21407 -0.111027 1.58729 0.299108L9.71229 9.22768C9.89611 9.42968 10 9.70855 10 10C10 10.2914 9.89611 10.5703 9.71229 10.7723L1.58729 19.7009C1.21407 20.111 0.620589 20.0977 0.26172 19.6712Z"
                fill="#FAFAFA"/>
        </svg>
      </div>
      <div class="btn-svg-form-end-color little">
        <svg width="40%" height="40%" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path
              d="M9.63587 19.901L9.62917 19.8971L9.60594 19.8835C9.58615 19.8719 9.55785 19.855 9.52162 19.8331C9.44915 19.7893 9.34486 19.7252 9.21329 19.6413C8.95026 19.4737 8.57762 19.2268 8.13184 18.9058C7.24179 18.2648 6.05253 17.3226 4.8601 16.1184C2.50032 13.7353 0 10.1947 0 5.83342C0 2.57998 2.52677 0 5.57692 0C7.37065 0 8.97674 0.887888 10 2.27959C11.0233 0.887888 12.6294 0 14.4231 0C17.4732 0 20 2.57998 20 5.83342C20 10.1947 17.4997 13.7353 15.1399 16.1184C13.9475 17.3226 12.7582 18.2648 11.8682 18.9058C11.4224 19.2268 11.0497 19.4737 10.7867 19.6413C10.6551 19.7252 10.5509 19.7893 10.4784 19.8331C10.4421 19.855 10.4138 19.8719 10.3941 19.8835L10.3708 19.8971L10.3641 19.901L10.3613 19.9027C10.1357 20.0324 9.8643 20.0324 9.6387 19.9027L9.63587 19.901Z"
              fill="#FAFAFA"/>
        </svg>
      </div>
      <div class="btn-svg-form-end-color">
        <svg width="40%" height="40%" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path
              d="M9.63587 19.901L9.62917 19.8971L9.60594 19.8835C9.58615 19.8719 9.55785 19.855 9.52162 19.8331C9.44915 19.7893 9.34486 19.7252 9.21329 19.6413C8.95026 19.4737 8.57762 19.2268 8.13184 18.9058C7.24179 18.2648 6.05253 17.3226 4.8601 16.1184C2.50032 13.7353 0 10.1947 0 5.83342C0 2.57998 2.52677 0 5.57692 0C7.37065 0 8.97674 0.887888 10 2.27959C11.0233 0.887888 12.6294 0 14.4231 0C17.4732 0 20 2.57998 20 5.83342C20 10.1947 17.4997 13.7353 15.1399 16.1184C13.9475 17.3226 12.7582 18.2648 11.8682 18.9058C11.4224 19.2268 11.0497 19.4737 10.7867 19.6413C10.6551 19.7252 10.5509 19.7893 10.4784 19.8331C10.4421 19.855 10.4138 19.8719 10.3941 19.8835L10.3708 19.8971L10.3641 19.901L10.3613 19.9027C10.1357 20.0324 9.8643 20.0324 9.6387 19.9027L9.63587 19.901Z"
              fill="#FAFAFA"/>
        </svg>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ButtonPushMesseng",

  data() {
    return {
      buttomText: 'Отправить сообщение',
      timeNum: null,
    }
  },
  mounted() {
    document.getElementById('text-box').innerHTML = 'Отправить сообщение'
    document.getElementsByClassName('time-action-btn')[1].style.display = "none"
    setTimeout(() => {
      document.getElementsByClassName('btn-push-message')[1].classList.toggle("time-action-btn-disable")
    }, 3000);
  },
  methods: {
    updateTime() {
      console.log(document.getElementsByClassName('btn-push-message')[0].classList)
      document.getElementsByClassName('btn-push-message')[0].classList.toggle("time-action-btn-disable")
      document.getElementsByClassName('btn-push-message')[2].classList.toggle("time-action-btn-disable")
      document.getElementById('text-box').innerHTML = 'Отправить повторно'
      document.getElementsByClassName('time-action-btn')[1].style.display = "flex"
      let timer;
      let x = 5;
      countdown();

      function countdown() {
        if (x < 10) {
          document.getElementById('rocket').innerHTML = '00:0' + x
        } else {
          document.getElementById('rocket').innerHTML = '00:' + x
        }
        x--;
        if (x < 0) {
          clearTimeout(timer);
          document.getElementsByClassName('btn-push-message')[0].classList.toggle("time-action-btn-disable")
          document.getElementsByClassName('btn-push-message')[2].classList.toggle("time-action-btn-disable")
          document.getElementsByClassName('time-action-btn')[1].style.display = "none"
          window.open('http://google.com')
          document.getElementById('text-box').innerHTML = 'Отправить сообщение'
        } else {
          timer = setTimeout(countdown, 1000);
        }
      }
    },
  },
}
</script>

<style scoped>
.btn-svg {
  margin-top: 3em;
  display: flex;
  justify-content: center;
}

.btn-svg > div {
  margin: 1em;
}

.btn-svg-form-end-color {
  transition-duration: .2s;
  cursor: pointer;
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  gap: 8px;
  width: 52px;
  height: 52px;
  background: linear-gradient(90deg, #D7650F 0%, #E1250A 100%);
  border-radius: 10px;
}

.btn-svg-form-end-color:hover {
  background: linear-gradient(90deg, #D7650F 0%, #E1250A 100%);
  box-shadow: 0px 8px 24px rgba(215, 101, 15, 0.7);
  border-radius: 40px;
}

.btn-svg-form-end-color:active {
  background: linear-gradient(90deg, #853900 0%, #AA1500 100%);
  border-radius: 40px;
  box-shadow: none;
}

.little {
  width: 36px;
  height: 36px;
}

.main {
  display: flex;
  flex-direction: column;
}

.main > p {
  transition-duration: .2s;
  cursor: pointer;
  margin: 0 auto;
  font-family: 'Inter';
  font-style: normal;
  font-weight: 400;
  font-size: 20px;
  line-height: 24px;
  display: flex;
  align-items: center;
  color: #FF6E00;
}

.main > p:hover {
  background: linear-gradient(90deg, #D7650F 0%, #E1250A 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
  text-fill-color: transparent;
  text-shadow: 0px 8px 24px rgba(215, 101, 15, 0.7);
}

.main > p:active {
  background: linear-gradient(90deg, #853900 0%, #AA1500 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
  text-fill-color: transparent;
  text-shadow: none;
}

.btn-push-message > p {
  text-align: center;
  padding: 0;
  margin: 0;
}

.time-action-btn-disable {
  background: linear-gradient(90deg, #8A8A8A 0%, #505050 100%) !important;
  font-family: 'Inter';
  opacity: 0.5;
}

.time-action-btn {
  transition-duration: .2s;
  display: none;
  flex-direction: row;
  align-items: center;
  padding: 0 4px;
  gap: 10px;
  width: 44px;
  height: 24px;
  background: #C4250E;
  border-radius: 5px;
  flex: none;
  order: 1;
  flex-grow: 0;
  font-size: 13px;
  line-height: 16px;
  justify-content: center
}

.btn-main {
  margin: 3em;
  display: flex;
  justify-content: space-around;
  flex-wrap: wrap;
}

.btn-push-message {
  transition-duration: .2s;
  cursor: pointer;
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  gap: 8px;
  padding: 16px 24px;
  font-family: 'Inter';
  font-style: normal;
  font-size: 20px;
  line-height: 24px;
  text-align: center;
  color: #FAFAFA;
  background: linear-gradient(90deg, #D7650F 0%, #E1250A 100%);
  border-radius: 10px;
}

.btn-push-message:hover {
  background: linear-gradient(90deg, #D7650F 0%, #E1250A 100%);
  box-shadow: 0px 8px 24px rgba(215, 101, 15, 0.7);
  border-radius: 40px;
}

.btn-push-message:active {
  background: linear-gradient(90deg, #853900 0%, #AA1500 100%);
  box-shadow: none;
  border-radius: 40px;
}
</style>