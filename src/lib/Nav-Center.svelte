<main id="nav-center"><slot /></main>
 <style>
    
    #nav-center{
    position: absolute;
    left: 50%;
    transform: translate(-50%);
    cursor: text;
    font-size: 15px;
    border-radius: 5px;
    transition: 0.1s background, 0.3s color, 0.3s fill;
    display: flex;
    justify-content: center;
    align-items: center;
    background: none;
    outline: none;
    border: none;
    color: var(--toolBarHover);
    text-align: center;
    background: var(--bgMain);
    height: 36px;
    }
 </style>