body, html {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
    background-color: var(--Dark-blue-MBG);
}

:root {
    //primary
    --Soft: hsl(215, 51%, 70%);
    --Cyan: hsl(178, 100%, 50%);

    //neutral
    --Dark-blue-MBG: hsl(217, 54%, 11%);
    --Dark-blue-CBG: hsl(216, 50%, 16%);
    --Dark-blue-line: hsl(215, 32%, 27%);
    --White: hsl(0, 0%, 100%);
}

.container {
    width: 100%;
    height: 100vh;
    display: grid;
    place-items: center;

}

main {
    width: 20rem;
    height: 34rem;
    display: flex;
    flex-direction: column;
    justify-content: center;  
    align-items: center;
    background-color: var(--Dark-blue-CBG);
    border-radius: 10px;
    box-shadow: 0px 5px 0px 3rem hsla(216, 50%, 16%, 0.2), 0px 2rem 0px 1rem hsla(216, 50%, 16%, 0.2);
}

.equilibrium-img {
    border-radius: 10px;
    width: 17rem;
    height: 17rem; 
    margin-top: 0.75rem;
}

.text {
    height: 6rem;
    font-family: "Outfit";
    padding: 5px;
    margin: 0.5rem;

    p:first-of-type {
        color: var(--White);
        font-size: 18px;
        font-weight: 600;
        left: 2rem;
        margin-left: 0.75rem;
    }

    p:first-of-type:hover {
        color: var(--Cyan);
        cursor: pointer;
    }

    p:nth-of-type(2) {
        color: var(--Soft);
        margin-left: 0.75rem;
    }

}

.sale {
    width: 17rem;
    display: flex;
    justify-content: space-between;

    .time, .cost {
        display: flex;
        flex-direction: row;
        align-items: center;

        p {
            margin-left: 0.3rem;
            font-family: "Outfit";
        }
    }

    .cost p {
        color: var(--Cyan);
    }

    .time p{
        color: var(--Soft);
    }
    border-bottom: 1px solid var(--Dark-blue-line);
}

.avatar {
    display: flex;
    align-items: center;
    width: 17rem;
    margin-top: 0.5rem;
    img {
        width: 2rem;
        border: 1.5px solid var(--White);
        border-radius: 50%;
    }

    p {
        margin-left: 1rem;
        color: var(--Soft);
        font-family: "Outfit";

        span {
            color: var(--White);
        }

        span:hover {
            color: var(--Cyan);
            cursor: pointer;
        }
    }
}
