<template>
 <div class="container">
   <form action="#" class="card">
     <h2 class="card__title">Регистрация</h2>
     <p class="card__account">Уже есть аккаунт? <a href="#" class="card__link">Войти</a> </p>
     <div class="card__inputs">
       <label for="name" class="card__label">Имя</label>
       <input type="text" id="name" class="card-item" placeholder="Введите Ваше имя">

       <label for="mail" class="card__label">Email</label>
       <input type="email" id="mail" class="card-item" placeholder="Введите ваш email">

       <label for="number" class="card__label">Номер телефона</label>
       <input type="number" id="number" class="card-item" placeholder="Введите номер телефона">
     </div>
     <label for="lang" class="card__label">Язык</label>
     <select name="lang" id="lang" class="card-item">
       <option value="lang" class="card_default" selected>Язык</option>
       <option value="rus" class="lang">Русский</option>
       <option value="eng" class="lang">Английский</option>
       <option value="chi" class="lang">Китайский</option>
       <option value="isp" class="lang">Испанский</option>
     </select>
     <div class="card__condition">
       <input type="checkbox" name="able" class="card__input-checkbox"> Принимаю <a href="#" class="card__link"> условия </a> использования
     </div>
     <button type="submit" class="card__button">Зарегистрироваться</button>
   </form>
 </div>
</template>

<script>

export default {
  name: 'Home'
}
</script>
