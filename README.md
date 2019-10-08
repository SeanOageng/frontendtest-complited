# frontendtest-complited
I realized that User Card Icons did not have the Active Icons, that is why you can only see the green background when you hover on the inactive icons.
This style sheet would work:  
.example li{
    cursor: pointer;
    display: block;
    width: 40px;
    height: 48px;
    float: left;
    margin: 20px;
    background-image: url(../images/icons-example.png);
    background-size: 131px;
    background-position-y: -48px;
    transition: all .25s ease-out;
}

example li.active {
    background-position: -65px -94px;
}
