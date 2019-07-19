<template>
   <section class="nav">
        <div class="nav-logo">
            <img height="160px" src="https://i.ibb.co/wzp4LBH/logo-white.png" alt="logo">
        </div>
        <div class="nav-menu">
            <div class="nav-menu-list">
                <a class = "nav-list-item" >About me</a>
                <a class = "nav-list-item" href="https://github.com/bpham30">GitHub</a>
                <a class = "nav-list-item" href="https://docs.google.com/document/d/1fNKdIj5AyS5Y0YZ8U31e9VubvPb8d7SsJ5xSMUCI1mw/edit?usp=sharing">Resume</a>
            </div>
        </div>
    </section>
</template>

<script>
export default {

}
</script>

<style lang="sass" scoped>
.nav
    background: #333
    display: flex
    flex-direction: column
    justify-content: space-around
    align-items: center
    .nav-logo
        margin: 20px auto
    .nav-menu
        width: 100%

.nav-menu-list
    padding: 0
    display: flex
    margin: 0
    color: white
    .nav-list-item
        text-decoration: none
        color: white
        width: 50%
        text-align: center
        background: #222
        padding: 10px 0
        cursor: pointer
        transition: background 300ms ease-in-out
        &:hover
            background: #444
        &first-of-type
            border-bottom: 5px solid #444
</style>
