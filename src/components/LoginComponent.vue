<script>
  export default {
    data() {
      return {
        username: '',
        password: '',
        showPassword: false,
        enlace: 'https://toward.studio/latest/retiring-our-404-goat'
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

<script setup>
    import Button from "../components/ButtonComponent.vue"
</script>

<template>
      <form @submit.prevent="login">
        <h1>Inicia Sesión</h1>
        <label for="username">Usuario</label>
        <input type="text" id="username" v-model="username" placeholder="Nombre usuario">
        <label for="password">Contraseña</label>
        <div class="password-container">
          <input
            :type="showPassword ? 'text' : 'password'"
            id="password"
            v-model="password"
            placeholder="Contraseña"
          >
          <button @click="togglePasswordVisibility" class="toggle-password-button">
            {{ showPassword ? 'Ocultar' : 'Mostrar' }} 
            <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-eyeglass-2" width="20" height="20" viewBox="0 0 24 24" stroke-width="1.5" stroke="#9e9e9e" fill="none" stroke-linecap="round" stroke-linejoin="round">
            <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
            <path d="M8 4h-2l-3 10v2.5" />
            <path d="M16 4h2l3 10v2.5" />
            <path d="M10 16l4 0" />
            <path d="M17.5 16.5m-3.5 0a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0 -7 0" />
            <path d="M6.5 16.5m-3.5 0a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0 -7 0" />
            </svg>
          </button>
        </div>
            <Button>
                <template #nameBtn>
                    <a href="https://toward.studio/latest/retiring-our-404-goat" target="_blank">
                        <slot>Login</slot>
                    </a>    
                </template>
            </Button>
                
            
      </form>
</template>

<style scoped>
    h1 {
        color: #ff556e;
    }
    form {
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        margin: 7rem;
        padding: 8rem;
        background-color: transparent;
        border-radius: 2rem;
        box-shadow: 0px 5px 15px 0px rgba(0, 0, 0, 0.35);
    }
    .password-container {
        position: relative;
    }
    .toggle-password-button {
        border-style: none;
        background-color: transparent;
        color: #ff556e;
        font-size: 14px;
        font-weight: 500;
        border-radius: 28px;
        position: absolute;
        top: 50%;
        transform: translateY(-50%);
        padding: 1rem;
    }
    .toggle-password-button:hover {
        background-color: #ff556e;
        color: white;
    }
    form input {
        border-style: none;
        background-color: transparent;
        padding: 2rem;
        outline: none;
    }
    form input::placeholder {
        letter-spacing: 1.3;
    }
    form label {
        color: #ff556e;
    }
    a {
        text-decoration: none;
        color: white;
    }
    a:hover {
        color: #ff556e;
    }
</style>