- 👋 Hi, I’m @Vinayroy116
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Vinayroy116/Vinayroy116 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
class computerdetails{
    constructor(P,R,p,n){
    this.processor=P
  
    switch (P){
    case "intel":
     
      this.prize = "inteli5 45000"
     
    break
    case "ryzen":
      this.prize = "ryzen5 25000"
      break
     
    }
    this.RAM = R
    
    switch (R){
      case "crucial":
      this.prize =  1500
    break
    case "kingstone":
      this.prize = 1250
      break
    }
    this.Pen = P
    
     switch (P){
      case "seagate":
      this.prize = 150
    break
    case "toshiba":
      this.prize = 125
      break
     
     }
    this.name = n 
    }
    display(){
      console.log(this.prize)
    }
  }  
  var vinay = new computerdetails("seagate")
  vinay.display()
  var prajwal = new computerdetails("toshiba")
  prajwal.display()

///example 2

  function mobiles(generation,cost){
    var amount = 0
    if(cost <15000){
      console.log("amount is not enough")
      return
    }
    switch(generation){
      case "4g":amount = 19000
      break
      case"5g": amount = 20000
      break
    }
      console.log(amount,)
  }
   
    mobiles("4g",25000 )

///example 

    function Account(dailylimit,deposit){
        var amount =0
        if(deposit <= 10000){
        console.log("u r dialylimit as been reached try some other time")
        return
        }
        switch(dailylimit){
          case "SBI":
          if(dailylimit >100){
            console.log(" have to be deposit")
          }
          amount = 2500
            break
            case "Axis":
              amount = 1500
              break
              
        }
        console.log(dailylimit,amount)
      }
      
      Account("Axis",100000)

////example

      let fruits=["apple","banana","orange"]
      fruits.push("grapes","papaya")
      for(i in fruits)
      {
        console.log(fruits[i])
      }
      fruits.pop()
      for(i in fruits)
      {
        console.log(fruits[i])
      }
      fruits.shift()
      for(i in fruits)
      {
        console.log(fruits[i])
      }
      fruits.unshift()
      for(i in fruits)
      {
        console.log(fruits[i])
      }
      
      const popped = fruits.pop();
      console.log(popped)
    
/// example 

  class internetconnection {
    constructor(v,Air,rel){
      this.vodafone =v
       
      switch(v){
        case "dataspeed":
          this.speed = "30.05mbps"
          break
          case "upload":
          this.speed = "32.06mbps"
          break
      }
    this.Airtel = Air
      
    }
    display(){
      console.log(this.speed)
    }
  }
  var vinay = new internetconnection("dataspeed")
  vinay.display()
  var prajwal = new internetconnection ("upload")
  prajwal.display()

  /// example 

  class car{
    constructor(innova,toyota,tata){
    this.inn=innova
    switch (innova){
    case "innova":this.prize=250000
    break
    case "toyota": this.prize=350000
    break
    case "tata":this.prize=500000
    break
    }
    this.toy=toyota
    this.ta=tata
    }
    display(){
      console.log(this.prize)
    }
  
  }
  
  var praju = new car("innova")
  praju.display()
  var praju = new car ("toyota")
  praju.display()
  var praju = new car ("tata")
  praju.display()
  
  
  ////example
  class fooditems{
    constructor(tif,lun,din){
      this.tiffen = tif 
      this.lunch = lun
      this.din = dinner
    }
  }
  
  var karan = new fooditems("idli","dosa","puri")
  var raju = new fooditems("rice","curries","dessert")
  
  class sweets extends fooditems{
    constructor(tif){
      super("kaju","jamun","kova")
      this.tiffen = tif
    }
    display()
    {
      console.log(this.tiffen,this.lunch)
    }
  }
  var vinay = new sweets("laddu")
  var kiran = new sweets("rasagula")
  kiran.display()
