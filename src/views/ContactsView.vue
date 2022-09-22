<template>
    <div style="height: 848px;" class="contacts">
    <div class="container">
      <h1 class="contacts_title">Контакты</h1>
      <div class="contacts_box">
          <div class="contacts_innerbox1">
              <div class="innerbox1_item">
                  <img src="../assets/img/tg-icon.png" alt="">
                  <div class="child_item"><a class="tg__link" href="https://t.me/faruq_obch">@hotskins</a> <p class="tg__text">Технические анонсы и новости</p></div>
              </div>
              <div class="innerbox1_item">
                <img src="../assets/img/tg-icon.png" alt="">
                <div class="child_item"><a class="tg__link" href="https://t.me/faruq_obch">@hotskins-help</a> <p class="tg__text">Поддержка пользователей сервиса</p></div>
              </div>
              <div class="innerbox1_item">
                <img src="../assets/img/email-icon.png" alt="">
                <div class="child_item"><a class="tg__link" href="mailto:hurraf2006@gmail.com">hello@hotskins.ru</a> <p class="tg__text">Для любых ваших вопросов</p></div>
              </div>
          </div>
          <hr class="hr_line">
          <div class="contacts_innerbox2">
              <div class="innerbox2_item">
                  <p class="innerbox2_text1">Beneficiary</p>
                  <p class="innerbox2_text2 itb1">Green Sequoia Square LTD</p>

              </div>
              <div class="innerbox2_item">
                <p class="innerbox2_text1">Reg. number</p>
                  <p class="innerbox2_text2 itb2">HE 405171</p>
              </div>
              <div class="innerbox2_item">
                <p class="innerbox2_text1">Beneficiary’s address</p>
                  <p class="innerbox2_text2 itb3">S35, Achaios Street, 5-th Floor, Office 17, P.C. 1101, Nicosia, Cyprus</p>
              </div>
          </div>
      </div>
    </div>
  </div>
</template>


<style scoped>
      .container{
    max-width: 1224px;
    width: 100%;
    margin: 0 auto;
    padding: 0 15px;
  }
  .contacts_title {
      padding-top: 48px;
      padding-bottom: 40px;
    font-size: 48px;
    line-height: 56px;
    font-family: 'rb';
    color: white;
  }
  .contacts {
    background-color: #272E3B;
  }
  .contacts_innerbox1 {
      padding-bottom: 41px;
      display: flex;
      align-items: center;
      justify-content: space-between;
  }
  .innerbox1_item {
      display: flex;
      align-items: center;
      gap: 24px;
  }
  .tg__link {
      font-size: 18px;
      line-height: 24px;
      font-family: 'rm';
      color: white;
  }
  .tg__text {
      font-size: 14px;
      line-height: 16px;
      font-family: 'rr';
      color: white;
  }
  .child_item {
display: flex;
flex-direction: column;
gap: 8px;

  }
  .hr_line {
      opacity: 50%;
  }
  .innerbox2_text1 {
      font-size: 16px;
      line-height: 22px;
       font-family: 'rr';
       color: white;
       opacity: 0.5;
}
.innerbox2_text2  {
    font-size: 16px;
      line-height: 22px;
       font-family: 'rr';
       color: white;
}
.innerbox2_item {
    display: flex;
    align-items: center;
}
.itb1 {
    margin-left: 124px;
}
.itb2 {
    margin-left: 113px;
}
.itb3 {
    margin-left: 50px;
}
.contacts_innerbox2 {
    margin-top: 40px;
    display: flex;
    flex-direction: column;
    gap: 16px;
}
</style>