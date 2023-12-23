<template>
    <div class="footerWrapper">
        <div class="footerWrapper__wrapperText">
            <div class="footerWrapper__title">
                <p class="footerWrapper__title-item">
                    We Have Branches All Over The World
                </p>
            </div>
            <div class="footerWrapper__text">
                <div class="footerWrapper__text-item">
                    The gradual accumulation of information about atomic and
                    small-scale behaviour during the first quarter of the 20th
                    century, which gave some indications about how small things
                    do behave, produced an increasing confusion which was
                    Heisenberg, and Born.
                </div>
            </div>
        </div>

    </div>
</template>
  
<script>

import "@fontsource/montserrat";

export default {
    name: 'footerWrapper',
}
</script>
    
<style>
.footerWrapper {
    background: var(--dark-background-color, #252B42);
    height: 429px;
    display: flex;
    align-items: center;
    justify-content: center;
}

.footerWrapper__wrapperText {
    width: 600px;
}

.footerWrapper__title-item {
    color: var(--light-text-color, #FFF);
    /* h2 */
    font-family: Montserrat;
    font-size: 40px;
    font-style: normal;
    font-weight: 700;
    line-height: 57px;
    /* 142.5% */
    letter-spacing: 0.2px;
}

.footerWrapper__text-item {
    color: var(--light-text-color, #FFF);
    /* paragraph */
    font-family: Montserrat;
    font-size: 14px;
    font-style: normal;
    font-weight: 500;
    line-height: 20px;
    /* 142.857% */
    letter-spacing: 0.2px;
}

@media (max-width: 375.98px) {
    .footerWrapper__wrapperText {
        padding: 20px;
    }
}
</style>
  