# This is the big header!
## This is the second big header!
### And so on...
#### ...and so on.

![Image of Ornn from League of Legends](https://ddragon.leagueoflegends.com/cdn/img/champion/splash/Ornn_2.jpg)

```
public int plagueDeaths(int population){

        int plagueDeaths = 0;
        
        double spreadPlague =  Math.random();
        
        if(spreadPlague <= 0.15){
            System.out.println("O' great Hammurabi! A plague is ravaging the land! Our population will surely suffer!");
            plagueDeaths = population / 2;
            this.population -= plagueDeaths;
            this.totalDeaths += plagueDeaths;
            return this.plagueDeaths = plagueDeaths;

        } else return this.plagueDeaths = plagueDeaths;
    }
```
- [ ] This is a list of To-Do's
- [x] This item has been completed.
- [ ] This item is not yet finished.
