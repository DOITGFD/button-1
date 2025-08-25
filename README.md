# button-1
button creation
[Uploading button .html…]()
<style>
    .subscribe-button{
        background-color: red;
        color:white;
        border: none;
        height: 50px;
        width: 135PX;
        border-radius: 4px;
        cursor:pointer;
        margin-right: 8px; 
        transition: opacity 0.15s;   
    }
    .subscribe-button:hover{
        opacity: 0.8;
    }
    .subscribe-button:active{
        opacity: o.8;
    }

    .join-button{
        background-color: white;
        color:rgb(44, 169, 218);
        border-color:rgb(77 ,181, 222);
        border-style: solid;
        height:50px;
        width: 80px;
        border-radius: 2px;
        cursor: pointer;
        margin-right: 8px;
        transition: background-color 0.15s;
    }
    .join-button:hover{
        background-color: rgb(53, 156, 196);
        color: white;
    }
    .join-button:active{
        opacity: 0.8;
    }
    .tweet-button{
        background-color: rgba(14, 149, 233, 0.955);
        color:white;
        border-radius: 50px;
        height: 50px;
        width: 100px;
        border-color: rgba(14, 149, 233, 0.955);
        border: none;
        cursor: pointer;
        transition: background-color 0.15s;
    }
    .tweet-button:hover{
        background-color: rgb(134, 203, 231);
        color: rgb(14, 163, 222);
				box-shadow: 5px 5px 5px rgba(0, 0, 0.15);
    }
    .tweet-button:active{
        opacity: 0.8;
    }
    

</style>

<button class="subscribe-button">
    SUBSCRIBE
</button>

<button class="join-button">
    JOIN
</button>

<button class="tweet-button">
    TWEET
</button>
