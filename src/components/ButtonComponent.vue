<template>
    <button class="button-download__button">
        <div>
            <slot name="svg"></slot>
        </div>
        <p>
            <slot name="nameBtn"></slot>
        </p>
    </button>
</template>

<style scoped>

.button-download__button {
    display: flex;
    margin: 5px;
    padding: 5px 20px;
    color: #ffff;
    text-transform: uppercase;
    border: 2px solid #ff556e;
    font-size: 14px;
    font-weight: 700;
    border-radius: 28px;
    background-color: #ff556e;
}
.button-download__button:hover {
    background-color: #fff;
    border: 2px solid #ff556e;
    color: #ff556e;
}
.button-download__button p {
    margin: auto;
    margin-left: 5px;
}
</style>