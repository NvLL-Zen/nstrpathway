<div class="pageSection">
    <slot>

    </slot>
</div>

<style>
    .pageSection {
        width: 100vw;
        height: 100vh;
        display: flex;
        align-items: center;
        justify-content: center;
    }

    @media only screen and (max-width: 768px)  {
        .pageSection {
            height: fit-content;
        }
    }
</style>