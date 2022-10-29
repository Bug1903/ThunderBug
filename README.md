
ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    overflow: hidden;
 
  }
  

  
  li:last-child {
    border-right: none;
  }
  
  li a {
    display: block;
    color: black;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
  }
  
  li a:hover:not(.active) {
    background-color: rgb(139, 136, 136);
  }

  section
  {
    position: absolute;
font-size: 90px;
color: #000000;
margin-top: 69px;
margin-left: 242px;
transition-timing-function: ease;
  }

  
  .words {
    color: #f4d03f;
    font-size: 0;
    line-height: 1.5;
  }
  
  .words span {
    font-size: 5rem;
    display: inline-block;
    animation: move 3s ease-in-out infinite;
  }
  
  @keyframes move {
    0% {
      transform: translate(-30%, 0);
    }
    50% {
      text-shadow: 0 25px 50px rgba(0, 0, 0, 0.75);
    }
    100% {
      transform: translate(30%, 0);
    }
  }
  
  .words span:nth-child(2) {
    animation-delay: 0.5s;
  }
  
  .words span:nth-child(3) {
    animation-delay: 1s;
  }
  
  .words span:nth-child(4) {
    animation-delay: 1.5s;
  }
  
  .words span:nth-child(5) {
    animation-delay: 2s;
  }
  
  .words span:nth-child(6) {
    animation-delay: 2.5s;
  }
  
  .words span:nth-child(7) {
    animation-delay: 3s;
  }
  



