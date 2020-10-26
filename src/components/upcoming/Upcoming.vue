<template lang="html">
    <main>
        <h1> Upcoming conferences </h1>
        <p> Register today! </p>
        <section class="card-grid">
            <div class="card">
                <h2>JavaScript conference</h2>
                <div class="image">
                    snygg bild
                </div>
                <p> Learn the latest frameworks on our online conference! </p>
            </div>

            <div class="card">
                <h2>Lego master builder class</h2>
                <div class="image">
                    snygg bild
                </div>
                <p> Learn to build amazing great works from our shared history. </p>
            </div>

            <div class="card">
                <h2>JavaScript conference</h2>
                <div class="image">
                    snygg bild
                </div>
                <p> Learn the latest frameworks on our online conference! </p>
            </div>

        </section>
    </main>
</template>

<script>
export default {
}
</script>

<style lang="sass" scoped>
@use '@/styles/base.sass'

$card-image-color: #e58f1a

main
    background-color: base.$primary-bg

h1
    color: base.$primary-fg
    // background-color: $primary-bg
    padding: 0.4em
    margin: 0.2em

main > p
    margin: 0px
    color: base.$primary-fg

.card-grid
    display: grid
    grid-template-columns: 1fr 1fr 1fr

.card
    border: 1px solid base.$primary-fg
    padding: 0em
    margin: 0.4em

    h2
        margin-top: 0px
        margin-bottom: 0px
        font-size: 1.2em
        padding: 0.2em
        color: base.$primary-fg
        height: 2.5em

    .image
        height: 10em
        background-color: $card-image-color

    &:hover
        cursor: pointer
        box-shadow: 0.3em 0.3em 4px 0.15em #050d64
</style>
