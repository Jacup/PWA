<template>
    <div class="nav">
        <img class="logo logo-contain" src="@/static/icon.png">
        <div class="nav-links">
            <span>
                <NuxtLink class="item" to="/">Strona domowa</NuxtLink>
            </span>
            <span>
                <NuxtLink class="item" to="/onas">O nas</NuxtLink>
            </span>
            <span>
                <NuxtLink class="item" to="/onas">Galeria</NuxtLink>
            </span>
        </div>

    </div>
</template>

<script>

</script>
<style scoped>
.nav {
    display: flex;
    /* flex-direction: column; */
    justify-content: space-between;
    align-items: center;
    height: 100%;
    width: 100%;
    border-radius: 10px;
    background-color: #757575;
    border-width: 10px;
    max-height: 100px;
    min-height: 100px;
    max-width: 100vw;
    min-width: 200px;
}

.logo {
    width: 100px;
    height: 100px;
    margin-left: 2vw;
}

.logo-contain {
    object-fit: contain;
    object-position: center;
}

.nav-links {
    display: flex;
    flex-direction: row;
    height: 100%;
}

/* px, rem, em, vh, vw, % */
.item {
    margin-inline: 3px;
    padding: 15px 32px;
    border-radius: 4px;
    font-family: Arial, Helvetica, sans-serif;
    font-size: large;
    text-transform: uppercase;
    background-color: #e7e7e7;
    /* Green */
    border: none;
    color: black;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
}

.item:hover {
    background-color: #00E676;
    /* Green */
    color: white;
}
</style>

