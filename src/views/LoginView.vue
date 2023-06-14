<template>
    <main>
        <h1>Hola Login</h1>
        <form>
            <label for="">Usuario</label>
            <input type="text">
            <label for="">Contraseña</label>
            <input type="text">
            <button type="submit">Login</button>
        </form>
    </main>
</template>

<style>
form {
    display: flex;
    flex-direction: column;
    align-items: center;
}
form input, form button {
    margin: 0.2rem;
}
form label {
    align-self: flex-start;
}
</style>