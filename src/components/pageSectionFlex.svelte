<div class="pageSectionFlex">
    <slot>

    </slot>
</div>

<style>
    .pageSectionFlex {
        width: 100%;
        height: fit-content;
        display: flex;
        align-items: center;
        justify-content: center;

        
    }

    @media only screen and (max-width: 768px)  {
        .pageSectionFlex {
            height: fit-content;
        }
    }
</style>