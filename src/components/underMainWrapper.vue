<template>
    <div class="underMainWrapper">
        <div class="underMainWrapper__listFacts">
            <div class="underMainWrapper__listFacts-item">
                <div class="underMainWrapper__listFacts-item-photo">
                    <img href="#!" src="../static/underMainWrapper__listFacts-item-photo1.svg" alt="header_logo"
                        class="underMainWrapper__listFacts-item-photo-item" />
                </div>
                <div class="underMainWrapper__listFacts-item-title">
                    <p class="underMainWrapper__listFacts-item-title-item">
                        Peace of Mind
                    </p>
                </div>
                <div class="underMainWrapper__listFacts-item-text">
                    <p class="underMainWrapper__listFacts-item-text-item">
                        So it really behaves like neither. Now we have given up.
                    </p>
                </div>
            </div>
            <div class="underMainWrapper__listFacts-item">
                <div class="underMainWrapper__listFacts-item-photo">
                    <img href="#!" src="../static/underMainWrapper__listFacts-item-photo2.svg" alt="header_logo"
                        class="underMainWrapper__listFacts-item-photo-item" />
                </div>
                <div class="underMainWrapper__listFacts-item-title">
                    <p class="underMainWrapper__listFacts-item-title-item">
                        Set For Life
                    </p>
                </div>
                <div class="underMainWrapper__listFacts-item-text">
                    <p class="underMainWrapper__listFacts-item-text-item">
                        They were used to create the machines that launched
                    </p>
                </div>
            </div>
            <div class="underMainWrapper__listFacts-item">
                <div class="underMainWrapper__listFacts-item-photo">
                    <img href="#!" src="../static/underMainWrapper__listFacts-item-photo3.svg" alt="header_logo"
                        class="underMainWrapper__listFacts-item-photo-item" />
                </div>
                <div class="underMainWrapper__listFacts-item-title">
                    <p class="underMainWrapper__listFacts-item-title-item">
                        100% Satisfaction
                    </p>
                </div>
                <div class="underMainWrapper__listFacts-item-text">
                    <p class="underMainWrapper__listFacts-item-text-item">
                        So it really behaves like neither. Now we have given up.
                    </p>
                </div>
            </div>
        </div>
        <div class="underMainWrapper__title">
            <p class="underMainWrapper__title-top">
                Industry
            </p>
            <p class="underMainWrapper__title-bottom">
                Problems trying to resolve the conflict between the two major realms of Classical physics: Newtonian
                mechanics
            </p>
        </div>
        <div class="underMainWrapper__listPeoples">
            <div class="underMainWrapper__listPeoples-item">
                <div class="underMainWrapper__listPeoples-item-photo">
                    <img href="#!" src="../static/underMainWrapper__listPeoples-item-photo1.svg" v
                        alt="underMainWrapper__listPeoples-item-photo">
                </div>
                <div class="underMainWrapper__listPeoples-item-text">
                    <p class="underMainWrapper__listPeoples-item-text-item">
                        Slate helps you see how many more days you need to work to reach your financial goal for the month
                        and year.
                    </p>
                </div>
                <div class="underMainWrapper__listPeoples-item-stars">
                    <img href="#!" src="../static/stars.svg" alt="underMainWrapper__listPeoples-item-photo" >
                </div>
            </div>
            <div class="underMainWrapper__listPeoples-item">
                <div class="underMainWrapper__listPeoples-item-photo">
                    <img href="#!" src="../static/underMainWrapper__listPeoples-item-photo2.svg"
                        alt="underMainWrapper__listPeoples-item-photo">
                </div>
                <div class="underMainWrapper__listPeoples-item-text">
                    <p class="underMainWrapper__listPeoples-item-text-item">
                        Slate helps you see how many more days you need to work to reach your financial goal for the month
                        and year.
                    </p>
                </div>
                <div class="underMainWrapper__listPeoples-item-stars">
                    <img href="#!" src="../static/stars.svg" alt="underMainWrapper__listPeoples-item-photo" >
                </div>
            </div>
            <div class="underMainWrapper__listPeoples-item">
                <div class="underMainWrapper__listPeoples-item-photo">
                    <img href="#!" src="../static/underMainWrapper__listPeoples-item-photo3.svg"
                        alt="underMainWrapper__listPeoples-item-photo">
                </div>
                <div class="underMainWrapper__listPeoples-item-text">
                    <p class="underMainWrapper__listPeoples-item-text-item">
                        Slate helps you see how many more days you need to work to reach your financial goal for the month
                        and year.
                    </p>
                </div>
                <div class="underMainWrapper__listPeoples-item-stars">
                    <img href="#!" src="../static/stars.svg" alt="underMainWrapper__listPeoples-item-photo">
                </div>
            </div>
        </div>
    </div>
</template>
  
<script>

import "@fontsource/montserrat";

export default {
    name: 'underMainWrapper',
}
</script>
    
<style>
.underMainWrapper {
    background: var(--light-gray-1, #FAFAFA);
    padding-top: 110px;
    padding-bottom: 120px;
}

.underMainWrapper__listFacts {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
}


.underMainWrapper__listFacts-item {
    width: 325px;
    display: flex;
    align-content: center;
    flex-wrap: wrap;
    flex-direction: column;
    align-items: center;
}

.underMainWrapper__listFacts-item-title-item {
    color: var(--text-color, #252B42);
    text-align: center;
    /* h5 */
    font-family: Montserrat;
    font-size: 16px;
    font-style: normal;
    font-weight: 700;
    line-height: 24px;
    /* 150% */
    letter-spacing: 0.1px;
}

.underMainWrapper__listFacts-item-text {
    width: 234px;
}

.underMainWrapper__listFacts-item-text-item {
    color: var(--second-text-color, #737373);
    text-align: center;
    /* paragraph */
    font-family: Montserrat;
    font-size: 14px;
    font-style: normal;
    font-weight: 500;
    line-height: 20px;
    /* 142.857% */
    letter-spacing: 0.2px;
}

.underMainWrapper__title {
    display: flex;
    flex-direction: column;
    align-items: center;
    flex-wrap: nowrap;
    margin-top: 70px;
}

.underMainWrapper__title-top {
    color: var(--text-color, #252B42);
    /* h2 */
    font-family: Montserrat;
    font-size: 40px;
    font-style: normal;
    font-weight: 700;
    line-height: 57px;
    /* 142.5% */
    letter-spacing: 0.2px;
}

.underMainWrapper__title-bottom {
    color: var(--second-text-color, #737373);
    text-align: center;
    /* paragraph */
    font-family: Montserrat;
    font-size: 14px;
    font-style: normal;
    font-weight: 500;
    line-height: 20px;
    /* 142.857% */
    letter-spacing: 0.2px;
    width: 470px;
    margin-top: -10px;
}

.underMainWrapper__listPeoples {
    display: flex;
    justify-content: center;
    margin-top: 132px;
    flex-wrap: wrap;
}

.underMainWrapper__listPeoples-item {
    display: flex;
    width: 297px;
    flex-direction: column;
    align-items: center;
    border-radius: 5px;
    border: 1px solid #DEDEDE;
    background: var(--light-background, #FFF);
    margin-right: 30px;
}

.underMainWrapper__listPeoples-item-photo {
    margin: 36px 0 10px 0;
}

.underMainWrapper__listPeoples-item-text-item {
    color: var(--second-text-color, #737373);
    text-align: center;
    /* paragraph */
    font-family: Montserrat;
    font-size: 14px;
    font-style: normal;
    font-weight: 500;
    line-height: 20px;
    /* 142.857% */
    letter-spacing: 0.2px;
    width: 227px;
}

@media (max-width: 375.98px) {
    .underMainWrapper__title-bottom {
            width: 360px;
    }

    .underMainWrapper__listPeoples-item {
        margin-bottom: 33px;
    }
}
</style>
  