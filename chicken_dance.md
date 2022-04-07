
function chicken_stationary{
    repeat(4){
        hands();
        cluck();
        shake();
        clap();
    }
}

main{
    repeat(5){
        squat();
    }

    chicken_stationary();

    repeat(4){
        rightKick();
        leftKick();
    }

    chicken_stationary();

    repeat(4){
        leftWave();
        rightWave();
    }

    repeat(3){
        circle();
    }

    repeat(2){
        chicken_stationary();
    }

    pose();
}