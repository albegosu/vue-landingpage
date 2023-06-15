<template>
    <main>
      <h1>Hola Login</h1>
      <form @submit.prevent="login">
        <label for="username">Usuario</label>
        <input type="text" id="username" v-model="username">
        <label for="password">Contraseña</label>
        <div class="password-container">
          <input
            :type="showPassword ? 'text' : 'password'"
            id="password"
            v-model="password"
          >
          <button @click="togglePasswordVisibility" class="toggle-password-button">
            {{ showPassword ? 'Ocultar' : 'Mostrar' }} contraseña
          </button>
        </div>
        <button type="submit">Login</button>
      </form>
    </main>
  </template>
  
  <style scoped>
  main {
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 5rem;
  }
  
  form {
    display: flex;
    flex-direction: column;
    align-items: center;
  }
  
  form input,
  form button {
    margin: 0.2rem;
  }
  
  form label {
    align-self: flex-start;
  }
  
  .password-container {
    position: relative;
  }
  
  .toggle-password-button {
    color: #ffff;
    border: 2px solid #ff556e;
    font-size: 14px;
    font-weight: 500;
    border-radius: 28px;
    background-color: #ff556e;
    position: absolute;
    top: 50%;
    transform: translateY(-50%);
  }
  </style>
  
  <script>
  export default {
    data() {
      return {
        username: '',
        password: '',
        showPassword: false
      };
    },
    methods: {
      login() {
      },
      togglePasswordVisibility() {
        this.showPassword = !this.showPassword;
      }
    }
  };
  </script>