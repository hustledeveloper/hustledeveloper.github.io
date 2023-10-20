.medium{
  background: linear-gradient(to bottom, #ffffff, #ffffff);
}
.medium h2{
  color: #000000;
}
.medium .heading span{
  color: rgb(0, 0, 0);
}
.medium .container{
  background: rgba(255, 255, 255, 0.4);
  border-radius: 1rem;
  padding: 2rem;
  margin: 1rem;
}
.medium .container .row{
  display: grid;
  grid-template-columns: repeat(2,1fr);
  flex-wrap: wrap;
}
.medium .container .row .col{
  display: grid;
}
.medium .container .col{
  position: relative;
  width: 90%;
  color: #fff;
  margin-top: .5rem;
}
.medium .container .col .bar{
  margin-bottom: 15px;
  padding: 10px;
  border-radius: 1rem;
  box-shadow: 0 4px 10px rgba(0,0,0,.2);
  background: rgba( 0, 0, 22, 0.9);
  transition: .2s;
}
.medium .container .col .bar:hover{
  transform: translateX(12px);
  box-shadow: 0 5px 8px rgba(0, 2, 68, 0.4);
}
.medium .container .col .bar .info{
  display: flex;
  align-items: center;
  justify-content: space-between;
  margin-bottom: 5px;
}
.medium .container .col .bar .info i{
  font-size: 2rem;
}
.medium .container .col .bar .info span{
  font-size: 1.8rem;
  font-weight: 500;
  font-family: 'Poppins';
  margin-left: .5rem;
}
.medium .container .col .bar .line{
  position: relative;
  width: 100%;
  height: 10px;
  background: rgb(212, 211, 211);
  border-radius: 6px;
}
.medium .container .col .bar .line:before{
  content: '';
  position: absolute;
  height: 100%;
  top: 0;
  left: 0;
  border-radius: 4px;
}

.medium .container .col .bar .network:before {
  width: 85%;
  background: #e03d0b;
}
