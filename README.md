/* header*/

.header__item{
    @media screen and (max-width:767px) {
            display: none;
          
        }
}

.header__menu{
    @media screen and (max-width:767px) {
            display: none;
        }

}

.header{
     @media screen and (max-width: 480px) {
       display: inline-flex;
           width: 480px;
   position: relative;  
 }  

  @media screen and (max-width: 780px){
display: inline-flex;
width: 780px;
  }

}


.header {
    position: relative;
    z-index: 10;
    border-bottom: 1px solid var(--border-color);

&__container {

        padding: 0 15px;
       /* width: 1200px;*/
        

  
                                                                    
@media screen and(max-width:767px) {
    display: flex;
   width: 767px;
    height: 60px;
}

@media screen and (min-width:768px) {
    min-width:786px ;
   margin-left: 0;
   margin-right: 0;
    
}

@media screen and (max-width:1199px) {
    width: 1199px;
    display: flex;
}
    }

    &__nav {
        
        display: flex;
        align-items: center;
        margin-right: auto;

        @media screen and (max-width:480px) {
           
            display: flex;
            
            margin-right: 0;
            
        }
    }

    &__logo {
        font-family: 'Raleway', sans-serif;
        font-weight: 700;
        font-size: 26px;
        line-height: 1.19;
        text-decoration: none;
        margin-right: 93px;
    }
        &__menu {
            list-style: none;
            font-weight: 500;
            display: flex;
            align-items: flex-start;
            justify-content: center;
            
        }
    
        &__contacts {
            display: block;
          
            align-items: center;
    
            text-decoration: none;
            font-family: inherit;
            font-weight: 500;
            list-style: none;
    
            padding-top: 32px;
            padding-bottom: 32px;
    
            fill: var(--container-preferences-color);
            color: var(--link-color);
    
            transition-property: fill, backgroud-color;
            transition-duration: 250ms;
            transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
            transition-delay: none;
           }
       &__contacts:hover {
            color: var(--secondary-color);
            fill: var(--secondary-color);
        }
    
        &__contacts:focus {
            color: var(--gradient-background-color);
        }
                &__contact {
                    display: flex;
                    align-items: center;

                   
                }
               &__link {
                                    font-weight: 500;
                                    @media screen and (max-width:767px) {
                                            display: none;
                                        }
                                }
         &__item {
                                                                    color: var(--small-section-title-color);
                                                                }
                                
                                                                &__item:not(:last-child) {
                                                                    margin-right: 50px;
                                                                }
                                
                                                                &__item:hover {
                                                                    color: var(--secondary-color);
                                                                }
                                                                           
&__button{

top: 10px;
right: 15px;
    display: inline-flex;
  
    margin: 0;
    padding: 0;
    border: none;
    background-color: transparent;
    margin-right: auto;
 @media screen and (min-width:767px) {
    display: none;
    position: absolute;
        top: 100%;
        left: 0;
        width: 100%;
        height: 600px;
 }

}
}
    
                              


.header__button .header__button--iconed-cross{
display: none;
width: 19px;
height: 19px;
}


.header__button.is-open .header__button--iconed-cross{
    display: block;
}

.header__button.is-open .header__button--iconed-open{
    display: none;
}

.header__button--dropped-down-menu{
   /*background-color: aqua;
   padding: 20px;
   text-align: center;
   font-size: 20px;*/
   display: block;
    width: 100%;
    max-width: 480px;
    max-height: 796px;
 
  
    background-color: #FFFFFF; 
    padding: 20px;
    box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.04), 0px 2px 4px rgba(0, 0, 0, 0.08), 0px 1px 3px rgba(0, 0, 0, 0.16);
font-family: 'Roboto';
    font-style: normal;
    font-weight: 500;
    font-size: 40px;
    line-height: 47px;
    letter-spacing: 0.02em;
    text-align: center;

    color: #212121;

   
    @media screen and (max-width:767px) {
        display: none;
         &.is-open{
        display: block;
    }

    }
    @media screen and (min-width:768px) {
              display: flex;
              justify-content: space-between;
              flex-grow: 1;
              
          }
}

.header__button--dropped-down-menu.is-open{
display: block;
}

.header .header__container {
    display: flex;
    align-items: center;
}

.header__logo--blue {
    color: var(--secondary-color);
}

.header__logo--black {
    color: var(--color-main);
}

.header__logo:hover {
    color: var(--secondary-color);
}



.header__contacts:hover .header__contact--iconed,
.header__contacts:focus .header__contact--iconed {
    fill: var(--secondary-color);
}

.header__contacts:not(:last-child) {
    margin-right: 50px;

    @media screen and (min-width:768px) {
        margin-right: 0;
    }
}


.header__contact--iconed {

    fill: var(--item-color);
    margin-right: 10px;

    transition-property: fill;
    transition-duration: 250ms;
    transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
    transition-delay: none;
}

.header__contact--iconed:hover {
    fill: var(--secondary-color);
}

.header__contact--iconed:focus {
    fill: var(--secondary-color);
}

.header__item--current {
    position: relative;
}


.header__item--current::after {
    content: '';

    position: absolute;
    left: 0;
    bottom: -32px;

    display: block;
    width: 100%;
    height: 5px;
    background-color: var(--secondary-color);

    opacity: 1;
    transition: opacity 250ms cubic-bezier(0.4, 0, 0.2, 1);
}

.header__item--blue {
    color: var(--secondary-color);
}

.header__item--blue:hover {
    color: var(--secondary-color);
}



.header__item--current.header__item--blue::after {
    border-radius: 2px;
}

.header__item--current {
    color: var(--secondary-color);
}

.header__item--current:active {
    color: var(--secondary-color);
}

