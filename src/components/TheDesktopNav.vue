<template>
    <section class="nav">
        <div class="nav-logo">
            <img height="200px" src="https://i.ibb.co/wzp4LBH/logo-white.png" alt="logo">
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
    position: fixed
    left: 0
    top: 0
    bottom: 0
    background: #333
    display: flex
    flex-direction: column
    align-items: center
    width: 20vw
    .nav-logo
        margin: 100px auto
    .nav-menu
        color: white

.nav-menu-list
    padding: 0
    .nav-list-item
        display: flex
        flex-direction: column
        text-decoration: none
        background: #222
        padding: 10px 20px
        text-align: center
        margin: 10px auto
        color: white
        cursor: pointer
        border-bottom: 1px solid transparent
        &:hover
            transition: 0.5s
            border-bottom: 1px solid white
            background: #444
            
</style>
