# Impossible cities

This paper outlines a summer 2020 design proposal for building car-free cities.

1. **Streets designed for mobility.** 
  * This proposal hinges on a re-design of what a city street looks like, to try to get less congestion, twice the average speed, and twice the total throughput (compared to, say, Manhattan New York). See <a href="#1">chapter 1</a>.
2. **Mobility for prosperity, not for speed.**
  * The main goal of the new design is to increase urban mobility. However, non-intuitively, the benefit is **not** faster commutes, but is instead higher wages & more social opportunities, as well as higher land values & better investment return rates. See <a href="#2">chapter 2</a>.
3. **Bonus features beyond mobility.**
  * The main goal is better mobility, but the design has a variety of other potential upsides. Cities like this should be greener, cleaner, fairer, safer, simpler, and more reliable & resilient. See <a href="#3">chapter 3</a>.
4. **This matters now.**
  * This is an important area of study right now, because there's about to be a huge influx of urban population, and a huge increase in urban construction. The construction of buildings will happen no matter what, so it would be good to try to do it in conjunction with the construction of modern transporation networks, rather than just repeating what was done in past decades. See <a href="#4">chapter 4</a>.
5. **This requires better funding models & better value capture agreements.**
  * Construction is **_very_** expensive. In order to fund the huge amount of construction required for new transportation networks, we need to get much better at **land value capture**. We need to set up reliable "fiscal engines" that can robustly recover the value created on each development project and reinvest it quickly on the next project. See <a href="#5">chapter 5</a>.




















<style>
 
body {
  color: #222222;
}

.hr {
  padding: 0em 40px 8em 0em;
  border-top: 12em solid white; /*transparent*/
  display: block;
  background-image: linear-gradient(#ffc4ae, white); /* #f58961 #DF4911 */
  position: relative;
  left: -20px;
  width: 100%;
  z-index: -1;
}


.chapter {
  /* margin-top: 3em !important; */
  padding: 1.8em 0em 1.8em 0em;
  line-height: 2;
}

h2 {
  color: #DF4911;
  font-size: 36px;
  font-weight: bold;
}

.h2 {
  color: #DF4911;
  font-size: 1.5em;
  font-weight: bold;
}

h3 {
  color: #DF4911;
  font-size: 1.5em; /* was 1.17em */
  font-weight: bold;
}

.h3 {
  color: #DF4911;
  font-size: 1.5em; /* was 1.17em */
  font-weight: bold;
}

.red {
  color: red;
}

.minor {
  color: grey;
  font-size: 0.8em;
  font-style: italic;
}

</style>





















<div id="contents-title">
  <div style="float:right;">Contents</div>
  <div id="contents-entries">
    <p>&nbsp;</p>
    <div>
      <details>
        <summary><a href="#1">1. Streets designed for mobility</a></summary>
        <ul>
          <li><a href="#comparison">2nd Ave vs. Impossible Street</a></li>
          <li><a href="#intersection">Impossible intersection design</a></li>
          <li><a href="#bike-sized">Bike-sized vehicles</a></li>
        </ul>
      </details>
    </div>
    <div>
      <details>
        <summary><a href="#2">2. Mobility for prosperity, not for speed</a></summary>
        <ul>
        </ul>
      </details>
    </div>
    <div>
      <details>
        <summary><a href="#3">3. Bonus features beyond mobility</a></summary>
        <ul>
        </ul>
      </details>
    </div>
    <div>
      <details>
        <summary><a href="#4">4. This matters now</a></summary>
        <ul>
        </ul>
      </details>
    </div>
    <div>
      <details>
        <summary><a href="#5">5. Why this is impossible</a></summary>
        <ul>
          <li><a href="#network-effect">Network effect problems</a></li>
          <li><a href="#location">Location problems</a></li>
          <li><a href="#cost">Cost problems</a></li>
          <li><a href="#land-value-capture">Land value capture & fiscal framework problems</a></li>
        </ul>
      </details>
    </div>
    <div>
      <details>
        <summary><a href="#appendixes">Appendixes</a></summary>
        <ul>
          <li><a href="#rules-of-thumb">Rules of thumb</a></li>
          <li><a href="#glossary">Glossary</a></li>
          <li><a href="#source-material">Source material</a></li>
          <li><a href="#notes" class="minor">Author's notes to self</a></li>
          <li><a href="#references">References</a></li>
        </ul>
      </details>
    </div>
  </div>
</div>





















<div class="hr"><a name="1"></a></div>

## <span class="chapter">_Chapter 1_ &mdash; Streets designed for mobility</span>

The Impossible City proposal hinges on a basic redesign of what a city street could look like. 

The Impossible design
  * replaces cars & buses with **bicycles** & **bike-sized** vehicles
  * replaces stop signs and traffic lights with **grade-separated** intersections
  * replaces outdoor, ground-level streets with **elevated, sheltered streets**

The result is:
  * less congestion and **twice the throughput**
  * **50% annual cost savings** over conventional public transit and private car ownership
  * **lower carbon emissions**, quieter streets, and less air pollution
  * **more trees**
  * a bit more available floorspace

<a name="comparison"></a>

  |---
  |  |  | 
  |:-:|:-|:-
  | | <object width="400" data="../svg/drawings/manhattan_ave.svg"></object><br><span class="h2">2nd Avenue, Manhattan</span><br> | <object width="400"   data="../svg/drawings/impossible_ave.svg"></object><br><span class="h2">Impossible Street Design</span><br>
  | **right-of-way** | 100-foot wide right-of-way<br>_(including sidewalks & street)_ | 100-foot wide right-of-way<br>_(including sidewalks & pair of center buildings)_
  | **sidewalks**    | two 20-foot wide sidewalks | two 15-foot wide sidewalks at ground-level <br> two 25-foot wide highline greenways with footpaths
  | **streets**      | one 60-foot wide open-air street      | two 30-foot wide enclosed streets elevated on 2nd floor
  | **lanes**        | six conventional vehicle lanes<br>_all one-way southbound_<br>_each lane 10 feet wide_ | eight bicycle lanes<br>_4 northbound & 4 southbound_<br>_each lane 6 feet wide, plus two shoulders, each 3 feet wide_
  | **vehicles**     | 1 bus-only lane<br> 4 lanes for cars, trucks, taxis, etc. <br> 1 lane parking & curbside loading | 8 lanes for bicycles and <a href="#bike-sized">bike-sized vehicles</a> vehicles
  | **cross-streets** | about 20 per mile | 8 per mile
  | **traffic lights** | about 20 per mile | none
  | **intersections** | at-grade conventional intersections | grade-separated intersections
  | **trees** | about 150 per mile | about 200 per mile
  | **speed limits**<br>as posted | 25 mph[^speed-limits] | 18 mph 
  | **actual speed**<br>average | 7.1 mph for cars[^nycdot] <br> 7.5 mph for buses[^nycdot] | 15 mph 
  | **vehicle<br>throughput** | 1 bus lane at about 6,000 people per hour (+/- 2,000)<br> 4 car lanes at about 1,000 people per hour each (+/- 400)<br>1 parking & delivery lane at 0 people per hour<br>**total:** about 11,000 people per hour | 8 bike lanes at about 3,500 people per hour per bike lane each (+/- 250 per hour)<br>**total:** about 28,000 people per hour
  | **sidewalk<br>throughput** | about 10,000 people per hour | about 10,000 people per hour
  | **bottom line** | less than half as many people<br>each moving half as fast | 
  |  | <a name="costs"></a><span class="h3">Costs</span> | 
  | **traffic fatalities** | 23 fatalities per million people per year | 1 fatality per million per year
  | **CO2 footprint<br>for transportation**<br>kg per person per year | 1,000 kg | 1 kg
  | **cost of public transit**<br>annual dollars per capita | $360 in fares paid by riders<br>$720 in city funded transit subsidies<br>**$1,080** total | $0
  | **private vehicle costs**<br>annual dollars per capita | $1,000<br>_mostly for cars_<br>_about 1 car per 10 people_ | $1,000<br>_mostly for bicycles, e-bikes, mopeds, scooters, etc._<br>_about 1 vehicle per person_
  | **air quality** | good | _really_ good
  | **noise levels** | noisier | quieter
  |  | <a name="costs"></a><span class="h3">Real estate</span> | 
  | **floorspace** | no real estate floorspace in street | 680,000 sqaure feet of floor space per mile


<a name="intersection">&nbsp;</a>

<figure style="text-align: center; padding-bottom: 4em;">
  <object width="1200" data="../svg/drawings/impossible_isometric.svg"> </object> 

  <figcaption style="font-size: 1.5em; font-weight: bold; color: #DF4911; text-align: center">Impossible intersection design</figcaption>
</figure>


### <a name="bike-sized"></a>Bike-sized vehicles

The <a href="#1">Impossible street design</a> replaces cars & buses with a wide variety of different kinds of **bicycles** & **bike-sized** vehicles. For this design "bike-sized" means:

  |---
  |  | limits for most vehicles | limits for licensed cargo vehicles
  |-:|:-|:-
  | **narrow** | 30 inch width limit | 48 inch width
  | **lightweight** | 111 pounds or less | 222 pounds
  | **underpowered** | 2 horsepower or lower | 4 horsepower 
  | **slow** | 18 mph speed limit city-wide<br>with automated enforcement | 15 mph 

  |---
  |  | <span class="h3">Examples</span> | 
  |:-:|:-|:-
  |  | <span class="minor">(The copyright to these pictures belongs to their respective owners. The pictures are used here under fair use, and are not included as part of the [Creative Commons Zero v1.0 Universal](https://raw.githubusercontent.com/nicky-nym/nicky-nym.github.io/master/LICENSE.txt) license/waiver that applies to the rest of this paper.)</span>  | 
  | **bicycles** | <img src="https://www.planetizen.com/files/styles/news_header_sm/public/images/BikeCommute.jpg" alt="bike commuter" height="100"/> <img src="https://kanwalkwilltravel.com/img/d695ee7c345f982116b270d93e17ede7.png" alt="bmx bike" height="100"/>
  | **family bicycles** | <img src="https://cupofjo.com/wp-content/uploads/2015/09/cup-of-jo-bikes-8-3.jpg" alt="family bicycle" height="100"/> <img src="https://www.macheesmo.com/wp-content/uploads/2018/09/cargo-bike1.jpg" alt="family bicycle" height="100"/> <img src="https://i.pinimg.com/originals/32/b0/ec/32b0ec61eaf544b3b482dc7faa9036f5.jpg" alt="family bicycle" height="100"/> <img src="https://momentummag.com/wp-content/uploads/2016/05/taga2main-1.jpg" alt="family bicycle" height="100"/>
  | **folding bicycles**<br>**&**<br>**compact hybrids** | <img src="https://theawesomer.com/photos/2019/04/halfbike_3_5.jpg" alt="halfbike" height="100"/> <img src="https://cdn.thisiswhyimbroke.com/images/halfbike-half-bike-640x534.jpg" alt="halfbike" height="100"/> <img src="https://avialbikes.com/wp-content/uploads/2019/04/YikeBike-folding-e-bike_2-1024x700.jpg" alt="YikeBike" height="100"/> <img src="http://39h10d29ck5a13hostsevnvx.wpengine.netdna-cdn.com/wp-content/uploads/2017/10/4-1.jpg" alt="YikeBike" height="100"/> <img src="https://gocycle.com/wp-content/uploads/2019/09/gxi-design0-mob-compressor.jpg" alt="Gocycle" height="100"/> <img src="https://cleantechnica.com/files/2019/01/jack-rabbit-mobility-ces-2019-las-vegas-1.jpg" alt="Jack Rabbit" height="100"/>
  | **electric bicycles** | <img src="https://sandiegoflyrides.com/wp-content/uploads/2018/01/18_Delite_25_black_outdoor-1024x683.jpg" alt="Riese & Muller Delite" height="100"/> <img src="https://sandiegoflyrides.com/wp-content/uploads/2018/01/18_Roadster_1-1024x682.jpg" alt="Riese & Muller Roadster" height="100"/>
  | **mopeds & scooters**<br>(electric) | <img src="https://assets.bwbx.io/images/users/iqjWHBFdfxIU/i.gOCVej_0Rw/v0/1000x-1.jpg" alt="Bird scooter" height="100"/> <img src="https://static.standard.co.uk/s3fs-public/thumbnails/image/2020/01/09/09/escooters0901a.jpg?w968" alt="electric scooter" height="100"/> <img src="https://static.timesofisrael.com/www/uploads/2019/07/000_1H28W6-640x400.jpg" alt="two-person scooter" height="100"/> <img src="https://smartelectricscooters.com/wp-content/uploads/2018/08/Best-Electric-Scooter-for-Adults-300x300.jpg" alt="sitting scooter" height="100"/> <img src="https://i.pinimg.com/originals/c3/21/9f/c3219fa308b64ff0599bf01164bfb402.jpg" alt="Bird sitting scooter" height="100"/>
  | **passenger trikes** | <img src="https://www.e-scooter.co/i/20/b7/f4/d206a1db125ad4834b79dca399.jpg" alt="Doohan iTango" height="100"/> <img src="https://cgmood.com/storage/previews/09-2019/6622/6622-13707.jpeg" alt="Doohan iTango" height="100"/> <img src="https://www.heradas.lt/image/image5c139ee727d78.png" alt="Doohan iTango" height="100"/> <img src="https://i0.wp.com/www.greenoptimistic.com/wp-content/uploads/2014/07/Toyota-i-Road-0001-537x358.jpg?fit=537%2C358&ssl=1" alt="Toyota iRoad" height="100"> <img src="https://images.hgmsites.net/lrg/2018-carver_100650884_l.jpg" alt="Carver" height="100"> <img src="https://www.e-scooter.co/i/3f/fc/1f/da2e9af5182ceea96b13bafe5a.jpg" alt="Carver" height="100"> <img src="https://i.servimg.com/u/f47/15/57/88/64/dscf2510.jpg" alt="Schaeffler Bio-Hybrid" height="100">
  | **cargo trikes** | <img src="https://bikeportland.org/wp-content/uploads/2018/10/download-2.jpeg" alt="Truck Trike" height="100"/> <img src="https://www.amsterdam-bicycle.com/wpcms/wp-content/uploads/E-Cargo-Trike-Classic-Narrow-Pearl-Blue-Metallic-Gloss.jpg" alt="Bakfiets.nl" height="100"/> <img src="https://sc01.alicdn.com/kf/HTB1PDOFXEvrK1RjSszfq6xJNVXap.jpg" alt="Ester Heavy Load Electric Assisted Cargo Trike" height="100"/> <img src="https://www.practicalcycle.com/wp-content/uploads/nihola_flex_open.jpg" alt="Nihola Flex" height="100"/> <img src="https://media.treehugger.com/assets/images/2017/04/17814216_280991905658092_1554833526111068713_o.jpg.860x0_q70_crop-scale.jpg" alt="Sanitov's movE" height="100"/> <img src="https://electricbikereview.com/wp-content/assets/2019/08/2019-rad-power-bikes-radburro-stock-truck-bed-1200x800-c-default.jpg" alt="Rad Power Bikes RadBurro" height="100"/>
  | **cargo vans** | <img src="https://fuseid.com/wp-content/uploads/2016/05/Truck-Trike-Hero-Render-Profile-1280x600.jpg" alt="UPS" height="100"/> <img src="https://s3-us-west-2.amazonaws.com/uw-s3-cdn/wp-content/uploads/sites/6/2018/10/24161707/Urban-Delivery-Solutions-Social-Media-Edit-041-still.jpg" alt="UPS" height="100"/> <img src="https://www.electrive.com/wp-content/uploads/2019/12/eav-cargo-pedelec-lasten-pedelec-2019-01-min-444x222.png" alt="eav" height="100"/> <img src="https://internationalfleetworld.com/wp-content/uploads/2019/09/eaVAN-350x263.jpg" alt="eav" height="100"/> <img src="https://i1.wp.com/www.electricbike.com/wp-content/uploads/2013/11/FedExTrike2.jpg?resize=504%2C378&ssl=1" alt="FedEx" height="100"/>
  | **motor-chairs<br>&<br>wheelchairs** | <img src="https://news-cdn.softpedia.com/images/news2/Meet-Speedster-the-World-s-Fastest-Wheelchair-2.jpg" alt="TankChair Speedster" height="100"> <img src="https://www.ultimatecarpage.com/images/gallery/fos08/Toyota-i-REAL-111493.jpg" alt="Toyota i-real" height="100"> <img src="https://upload.wikimedia.org/wikipedia/commons/e/e7/2007_Toyota_i-Real_02.jpg" alt="Toyota i-real" height="100"> 
  | **hoverboards<br>segways<br>ninebots<br>electric skateboards<br>etc.** | <img src="https://cdn.thisiswhyimbroke.com/images/segway-mini-300x250.jpg" alt="Ninebot Mini Pro" height="100"/> <img src="https://ninebot.com.sg/wp-content/uploads/2018/03/Ninebot_ONE-S2-rider-url-1000x1000.jpg" alt="Ninebot ONE S2" height="100"/> <img src="https://electrek.co/wp-content/uploads/sites/3/2019/03/DSC_1248-copy.jpg?quality=82&strip=all&w=678" alt="Kiwano KO1+" height="100"/>
  | **delivery robots** | <img src="https://cdn.geekwire.com/wp-content/uploads/2019/01/amazonscout-768x600.png" alt="Amazon scout" height="100"> <img src="https://techcrunch.com/wp-content/uploads/2019/04/AD03.jpg?w=730&crop=1" alt="brain OS" height="100"/> <img src="https://www.supermarketnews.com/sites/supermarketnews.com/files/styles/article_featured_retina/public/FedEx_SameDay_Bot_street_1.png?itok=Ml2UGf3F" alt="FedEx bot" height="100"/>




















<div class="hr"><a name="2"></a></div>

## <span class="chapter">_Chapter 2_ &mdash; Mobility for prosperity, not for speed</span>

The [impossible streets & intersections](#1) are designed to yield **faster travel times** and **higher throughput**, compared to conventional city streets in places like San Franisco or Manhattan New York.

### Beyond a faster commute

You might think that faster travel times would lead to faster commute times, but, surprisingly, that's usually not the case. Instead, when faster travel is possible, most people choose to use it to travel **further per day**, instead of using it to travel for **less time per day**. (See [Rules of thumb: Marchetti](#marchetti).)

The result of faster travel times is not shorter commute times for everyone, but is instead an increase in daily **kinematic range** for everyone.

### <a name="kinematic_range"></a>Kinematic range

  * **Kinematic range** is a measure of urban mobility. It's the number of destinations you can get to in 30 minutes or less _(or some other set amount of time)_.
  * Different cities have different kinematic ranges
    * In **Haxby, Montana**, there's not any traffic congestion, but there also aren't many places to go. With a car, in 30 minutes you can probably reach a total of about **a half dozen homes**, with perhaps **10 thousand square feet of floorspace**.
    * In **San Francsico**, there are lots of places to go, but there's a lot of congestion. In 30 minutes you can reach hundreds of thousands of homes, offices, and stores, with perhaps **500 million square feet of floorspace**.  San Francisco has a kinematic range that's about 50 thousand times larger than Haxby, Montana.

### <a name="congestion"></a>Congestion vs. kinematic range

  * A **congested** city is one where it's hard to get where you want to go, because there's too much traffic.
  * A **sleepy** little town is one where there's no traffic, but there's almost nothing in town to go to.
  * A **kinematic** city is one that has lots of destinations **_and_** they're all easy to get to.


```
TODO: add a diagram showing different ranges?
```

### <a name="who_cares"></a>Why does Kinematic Range matter?

Urban mobility isn't just a matter of convenience. Mobility is *fundamental* to a thriving lives and livelihoods. 

  * **For people**, having more destinations within reach means:
    * more **job offers** that are close enough to commute to
    * more **friends** & **family** who are actually close enough to drop by
    * more **schools** to choose from, and more **special classes**
    * more **doctors** to choose from, and a wider variety of **specialists** available
    * a wider variety of **churches** and **religious communities**
    * a wider variety of **events**, **meetups**, and **clubs**, and more people who share your interests
    * a wider variety of **[long tail](#glossary:long-tail)** destinations
  * **For shops**, **employers**, and **industry**, it means:
    * more **job candidates** to choose from
    * more **vendors** and **parts suppliers** to choose from
    * more **contractors** in different **specialized fields**
    * more **"industrial agglomeration"**, which leads to **"agglomeration economies"** (somewhat similar to the separate idea of "economies of scale")
  * **For 911 calls** & first responders, it means:
    * **faster response times** and **better incident outcomes**

### <a name="convenience"></a>Convenience, opportunity, prosperity

**Convenience** is one benefit of better urban mobility. Having more destinations in your kinematic range means it's easier to do the things you want to do.

Beyond just convenience, better mobility and kinematic range bring serious changes to the entire metabolism of a city, and to the amount of **opportunity** and **prosperity** available to people. 

### <a name="dividend"></a>15% dividend per doubling

Around the world, larger cities, with their larger kinematic ranges, tend to have higher wages than smaller cities.

As city size increases, when the number of people (and destinations) in the city grows by 100% (meaning a doubling in size), then the economy of the city tends to grow by about 115% (meaning it more than doubles in size), so that there is effectively a 15% "bonus" in per-capita economic output for everyone in the city.[^scale]

This 15% superlinear growth seems to apply to the whole physical and social metabolism of the city, rather than just the economic aspects of the city. The 15% surplus shows up in statistics about:
  * **wages**
  * **wealth**
  * **patents**
  * **AIDS cases**
  * **crime**
  * **restaurants**
  * **diversity of business services** available (meaning, how long the "[long tail](/glossary#long-tail)" of the city is)

```
TODO: add a graph illustrating 15% doubling
```

### <a name="incrementalist"></a>How Kinematic are existing cities?

```
TODO: comparison of public transit in Singapore vs. cars in Dallas-Fort Worth. (See Velotopia page 44.) 
```


### <a name="incrementalist"></a>How do existing cities try to become more Kinematic?

Existing cities work hard, and spend billions, to try to incrementally improve mobility and kinematic range.

Cities can improve kinematic range by **moving more people** or **moving people faster**
  * **public transit projects**
    * the **2nd Avenue Subway** project in New York
    * the **Transbay Transit Center** in San Francisco
  * **more highways**, or **more lanes**
    * the **Big Dig** in Boston
  * **more throughput per lane**
    * the **HOV Carpool Lanes** in Los Angeles
    * the **congestion pricing** in London

Cities can also improve kinematic range by **becoming denser**, so that more people and more destinations are nearby
  * **transit oriented development**
  * **dense urban cores**
  * **infill development**
  * **multi-use zoning**

### <a name="future"></a>Future possibilities

Someday, in the future, cities might also be able to improve kinematic range by using **newly invented transit options**
  * **hyperloop** transit tubes
  * **Boring company tunnels**
  * **flying cars**


### <a name="better"></a>Could we do better?

Existing cities, all over the world, have serious traffic congestion problems, despite spending billions on transit projects and on widening roads. As cities grow and economies grow, the congestion problems just get worse.

### <a name="transit_vs_cars"></a>Transit vs. cars

Here in the United States, in discussions about urban planning and transporation, many people fall into one of two opposing camps:

  * **pro-transit people** , who want to see
    * fewer cars on the road
    * less space set aside for parking
    * more bike lanes and bus lanes
    * more funding for some combination of subways, light rail, buses, bus rapid transit, and other public transit
  * **pro-status-quo "car" people**, who 
    * do not want to lose automobile lanes in return for bike lanes and bus lanes
    * do now want to pay the huge costs of creating and operating public transit systems
    * do not want to take slow, inconvenient, public transit options when they could just drive

### <a name="self_driving"></a>Self-driving cars & delivery drones

In addition to the **pro-transit** camp and the **pro-status-quo** camp, there's also a third camp, of people who are optimistic about new technologies for **automated, on-demand transporation**, like self-driving cars and delivery drones. 

**Proponents** of shared, self-driving cars point to advantages like the greatly reduced need for parking compared to conventional cars, yet the convenience of direct door-to-door routes.

**Opponents** of self-driving cars point to inherently low throughput-per-lane numbers for cars vs. buses and trains, and the real-world congestion problems that we're already seeing from on-demand car-share services like Lyft and Uber.

### <a name="micromobility"></a>Scooters & micromobility

Cities around the world are experimenting with whole range of other new transportation options, from dockless rental scooters to designated bike-share stations. The advent of electric bikes and electric scooters also opens new possibilities.

### <a name="best"></a>The best we could do...

Given what we know about the cost and throughput of cars, buses, and rail, and given what we know about the emerging new alternatives, what's the best we could possibly do?

If we could plan a whole urban transporation network from scratch, what's the optimal mix of different transit modes? Which options are the most affordable, and which ones maximize personal mobility, speedy deliveries, and kinematic range?

What follows is a design proposal for what I believe is a **simple**, **cheap**, **reliable**, **low-risk** transportation network that has **high throughput**, good **transit speed**, nearly **door-to-door** convenience, and takes up less space than roads, leaving more **land area** for parks and buildings.


### <a name="impossible"></a>"Impossible city" design proposal

The **Impossible city** is just one simple design for a more Kinematic city. I'm not suggesting that this is the best design; rather, I'm putting it out as a *straw-man* proposal, in hopes that it might be a step in the right direction, and that it might spark conversation that leads to better ideas.

### <a name="features"></a>What are the main design features?

The Impossible design calls for:

  * bikes & **bike-sized vehicles** only, instead of cars, trucks, buses, or trains
  * **electric vehicles** only, instead of gas engines
  * **grade-separated intersections** only, instead of traffic lights, stop signs, or roundabouts
  * **sheltered roads**, sheltered from wind and rain
  * **underground wiring**, instead of telephone poles and overhead power lines

### <a name="look_like"></a>What would it look like?

**A grid**
  * The Impossible design has a **grid of city blocks**, similar to the layout of cities like Manhattan New York. That's in contrast to older cities like Rome and Paris, which have more intricate street layouts, and in contrast to many 20th century suburban developments or new cities like Dubai, which often have more circular or curvy streets, or layouts that are intentionally asymmetrical, with cul-de-sacs and loops.
 
**A big grid**
  * Instead of the rectangular blocks that Manhattan has, the Impossible design has square blocks. Big blocks: more **like big Salt Lake City blocks** than little Portland, Oregon blocks.
  
**With normal buildings**
  * The buildings in each city block would just be normal buildings. They could be mid-rise or high-rise, in any sort of architectural style.

**But with sheltered streets**
  * The "streets" would look very different from normal city streets:
    * They would **not be outdoors**, but would instead be long breeze-way corridors inside a four-story building.
    * They would **not be at ground level**, but instead would be up on the second or third floor.
    * They would **not have intersections**, but instead would be "grade-separated", so that the east-west streets pass above the north-south streets.


### <a name="why"></a>Why is this a better design?

The Impossible design is built entirely around **bicycles**, **bike-sized electric vehicles**, and **sheltered streets** with **no interestions**. At first blush, it's hard to imagine that this is a practical design. It doesn't seem like an entire city could have no buses, trains, or cars, and still manage to move millions of people a day with reduced travel times and increased travel ranges.

It **seems** impossible, because cars **seem** like fast, long-range vehicles, and buses and trains **seem** like high-capacity transit. 

Cars **truly are** fast when they're on highways, but in cities cars are hugely inefficient and ineffective, requiring huge amounts of lane space per car, and traveling with high burst speeds but poor average speeds.

Buses and trains **truly are** high-capacity and high-throughput when everyone on them is going from point A to point B. If you have a group of 50 people who are all gathered together (e.g., at a hotel) and who all need to go to the exact same place (e.g., an office or work site) at the same time, then a bus is a wonderfully efficient and effective choice. But in a city, if people are starting from a variety of different places (different apartment buildings on different blocks), and going to a variety of different places (schools, stores, offices), then buses turn out to have quite poor average throughput.


### <a name="how"></a>How do you know this is better?

By building models and running simulations, and by combing through the available statistics about the different existing transportation modes in different cities.


### <a name="where"></a>Where would it be?

**Anywhere:** The impossible design does not depend on a particular climate, or on particular building materials. It's an anywhere-in-the world city, not just a European city, an African city, or an Arctic city.

It could be built on the outskirts of an existing city, or it could be built in a brand new "greenfield" site.

### <a name="how_much"></a>How much would it cost?

  * **The same as a regular city**
    * Construction costs, per square foot, would be about the same for buildings in a kinematic city as buildings in a regular city.
    * In a region with high construction costs, like California, constructing buildings in a kinematic city would be just as expensive as constructing buildings in other cities.
    * In places with lower construction costs, like the UAE, or China, constructing buildings in a kinematic city would cost about the same as building any other building. 
    
  * **Maybe slightly cheaper**
    * The simplest sorts of kinematic city designs could entirely omit some of the expensive transit systems found in conventional cities, such as subway systems and light rail. 
    * A simple kinematic city designs could also be composed entirely of mid-rise buildings, which are cheaper to build, per square foot, than either high-rise or low-rise buildings.

### <a name="how_long"></a>How long would it take?

  * **The same as regular construction**

























<div class="hr"><a name="3"></a></div>

## <span class="chapter">_Chapter 3_ &mdash; Bonus features beyond mobility</span>

|---
| <span class="h3">Existing city problems</span> | <span class="h3">Impossible improvements</span> |  |
|:-|:-:|:-:|:-:|:-:
| **traffic congestion** |  |  |
| **housing costs** are too high |  |  |
| **transportation costs** are too high |  |  |
| **not safe enough** |  |  |
| **not good for people's mental health** |  |  |
| **not resilient** after natural disasters and power failures |  |  |
| **limit mobility** of kids, elders, and people with disabilities |  |  |
| **not quickly alterable**<br>making one significant change can take decades |  |  |
| **not cheaply alterable**<br>it is staggeringly expensive to add subways or highways to an existing city |  |  |
| are **too few and too small**, by a factor of two, for everyone who will live in them by 2050 | 


### <a name="goals"></a>What are the design goals?

  * improved overall **urban mobility** & **kinematic range**
    * realize a 15% dividend in wages, wealth, patents, land value, etc.
    * increase economic prosperity
    * increase social prosperity
  * **more affordable** transportation and housing 
  * a **level playing field** for urban mobility
    * more **kid-friendly**
    * more **elder-friendly**
    * more **accessible** for people with disabilites
  * a **cleaner**, **quieter**, **safer** city
  * reduced **carbon footprint** and **air pollution**
  * a **more resilient** city and after natural disasters and power failures
  * **simplicity**, **durability**, and **reliability**
    
### <a name="comparison"></a>How would it compare?

|---
|  | Proposed Kinematic City | San Francisco | New York |
|-:|:-:|:-:|:-:|:-:
| **Trips**<br>annual, per million people | 1.2 billion | 1.2 billion[^google_eie] |  |
| **Commute time**<br>minutes per day<br>(average per commuter) | 60 minutes | 60 minutes | 76 minutes |
| **Traffic fatalities**<br>annual, per million people | 1 | 30 | 23
| **CO<sub>2</sub> footprint for transportation**<br>annual per capita | 1 kg | 2,000 kg | 1,000 kg
| **Commute kinematic range**<br>square feet | 5 billion | 1.25 billion |   |
| **Kinematic windfall**<br>wages, GDP, patents per capita, etc. | 1.3x | 1x |   |
| **Proximity to friends**<br>number of neighbors within 15 minutes | 2 million<br>(without car) | 1 million<br>(requires car) |
| **Proximity to places**<br>number of places within 15 minutes<br>library, coffee shop, playground, groceries | 2x<br>(without car) | 1x<br>(requires car)
| **Proximity to trees**<br>number of trees within 15 minutes | > 125,000 trees | > 125,000 trees |		
| **Cars**<br>per million people | 100 | 450,000 | 220,000	
| **Trucks**<br>per million people | 100 | 60,000 | 	
| **Buses, etc.**<br>buses, streetcars, light rail vehicles, etc.<br>per million people | 1 | 1,380 | 	
| **Cost to city to subsidize public transit**<br>annual dollars per capita | $0 | $720
| **Cost of public transit paid by riders**<br>annual dollars per capita | $0 | $360
| **Cost of car ownership**<br>gas, insurance, repairs, payments, etc.<br>annual dollars per capita | $0 | $4,000 | $2,000
| **Cost of bike ownership**<br>bicycles, mopeds, scooters, segways, trikes, etc.<br>annual dollars per capita | $1,000 | $100
| **Exercise while commuting**<br>minutes per day<br>(average per commuter) | 15 minutes<br>(if 3 of 4 bikes<br>are e-bikes) | 5 minutes | 	
| **Air quality** | _really_ good | good 
| **Noise levels** | slightly lower than<br>San Francisco | slightly more than<br>proposed city 
| **ADA accessibility**<br>percent of total city floor space | 90% | ?
| **Free-range kids** | yes | no		
| **Power-outage impact**<br>on transit times | no bikeway lights<br>(just daylight/moonlight) | no BART<br>no traffic lights
| **Daylighting**<br>Spatial Daylight Autonomy (sDA) percent<br>Annual Sun Exposure (ASE) percent<br>(also several others)
| **Home sizes**<br>square feet per person, average | 275 | 275 |
| **Office space**<br>square feet per person, average | 260 | 260 |
| **911 response time**<br>minutes, average | 4 minutes | 5.75 minutes |	
| **Housing costs**<br>monthly rent per apartment<br>(750 square feet) | > $1,000 | $3,750 |
|                   condo price, average | > $120,000 | $1.2 million
|---















<div class="hr"><a name="4"></a></div>

## <span class="chapter">_Chapter 4_ &mdash; Why this matters now</span>

In the next 30 years, **by 2050**, we expect another **2.5 billion more people** to be living in cities.[^growth]

To handle the influx, cities will build another **2.5 trillion square feet** of new buildings. These numbers can be hard to believe at first. For different projects by different authors, see the [notes about urban growth](#growth) below.




















<div class="hr"><a name="5"></a></div>

## <span class="chapter">_Chapter 5_ &mdash; Why this is impossible</span>

We know that:
* the world desparately needs more cities & bigger cities
* we can design new 21st century cities that would work far better for poeple than the default 20th century designs. 

Unfortunately, actually building cities this way is probably impossible, because of:
* <a href="#network-effect">network effect problems</a>
* <a href="#location">location problems</a>
* <a href="#cost">cost problems</a>
* <a href="#land-value-capture">land value capture & fiscal framework problems</a>



### <a name="network-effect"></a>Network effect problems

```
TODO:
```

### <a name="location"></a>Location problems

So, **where** could these new city designs actually be built? There are a few different types of locations, but they all have problems:
* infill & rebuilding in existing cities
* new suburbs & satellite cities around existing cities
* "new city" greenfield cities

#### Infill & rebuilding in existing cities

Zoning restrictions in existing cities prevent any large-scale changes to their spatial layout.

> "Three-quarters of the residential land in Los Angeles is restricted to single-family homes, according to UrbanFootprint, software that helps government and businesses understand cities and urban markets. In San Jose, the figure is 94%." [^buhayar]

Projects in existing cities can be staggeringly expensive.
  * **$4.5 billion** for the San Francisco **Transbay Transit Center & Salesforce Tower** <sup>[citation needed]</sup>
  * **$17 billion** for the **2nd Avenue Subway** project in New York <sup>[citation needed]</sup>
  * **$20 billion** for the **Hudson Yards** project in New York <sup>[citation needed]</sup>
  * **$21 billion** for the **Big Dig** in Boston <sup>[citation needed]</sup>
  * **$23 billion** for the **Riyadh Metro** <sup>[citation needed]</sup>
  * **$32 billion** to rebuild the **World Trade Center** in New York <sup>[citation needed]</sup>

> "Retrofitting cities, where cities already exist, can be up to three times more expensive than planning for infrastructure in advance of settlement." [^haas]

> "only about a quarter of New York City's 472 subway stations are wheelchair accessible" ... "subway officials ... plan to add elevators at 70 stations in the next five years." ... "The Metropolitan Transportation Authority ... estimates that accessibility fixes will cost about $78 million per station." [^fitzsimmons]


#### New suburbs & satellite cities


```
TODO:

Perhaps existing cities will absorb nearly all of the 2.5 billion additional people who will live in cities by 2050, but in doing so some of their suburbs will essentially develop into big satellite cities of their own right, so the Kinematic city ideas are relevant for how new developments in those satellite cities are designed.

If 4% of the people did move to entirely new cities, that would be 100 million people in new cities. A single new kinematic city could "just" be 10 million people.
```

#### "new city" greenfield cities

Building on a new empty, greenfield site is a lot less expensive than building in an existing city. New cities provide more space at lower cost per capita. New cities create value, and demand.<sup>[citation needed]</sup>

> "We are at the beginning of the next wave of urbanization — a period of 
> rapid growth in both area and population... The next wave of urbanization 
> will also be defined by its sheer size — a tripling of land cover in the 
> first half of this century alone. While the carrying capacity of existing 
> cities is under increasing strain, unsustainable urban growth threatens to 
> outstrip any mitigation efforts in our urban cores. The result is a need 
> for new sites of politics, housing, commerce, industry, and energy. One 
> solution is the accelerating development of greenfield cities around the world. 
> Building new cities from the ground up is a bold (and monumentally difficult) 
> attempt to relieve the strain on our currently overloaded urban systems. It 
> promises to build energy efficiency, sustainability, and resilience in to the core of a place."[^caspar]
> &mdash; Caspar Herzberg, Schneider Electric



### <a name="cost"></a>Cost problems

Constructing even small buildings is expensive. Constructing entire neighborhoods or cities requires not just building housing and office space, but also building all the transportation infrastruction for roads, street lights, traffic lights, bus shelters, subway stops, and more. Plus all of the utility infrastructure, including sewers, water supply, power lines, telephone lines, and the rest.

```
TODO:

  * spending is somewhere between the high hundreds of billions of dollars, and the low trillions of dollars
  * real estate development projects now operate at a scale where it is possible to complete a coordinated, monolithic, **privately financed $10 billion construction project**
```




### <a name="land-value-capture"></a>Land value capture & fiscal framework problems

Read more about [costs & land value](economics)

```
TODO: This requires better funding models & value capture agreements
```




















<div class="hr"><a name="appendixes"></a></div>

## <span class="chapter">_Appendixes_</span>

* [Rules of thumb](#rules-of-thumb)
* [Glossary](#glossary)
* [Source material](#source-material)
* [References](#references)










## <a name="rules-of-thumb"></a><span class="chapter">Rules of thumb</span>

  * <a name="marchetti"></a>**People tend to travel about one hour a day.**
    * For people who commute, the average commute is about 30 minutes each way.
    * For people who aren’t commuting, it is common to spend about an hour each day on other sorts of trips: chores, errands, appointments, etc.
    * This "one hour per day" number has been found to be surprisingly consistent across different cities in different centuries, different cultures, and different continents, regardless of the different modes of travel used to commute. This is called the **Marchetti constant** (named for Cesare Marchetti, although it was really Yacov Zahavi who first wrote about it).

  * **Some aspects of a city scale linearly.**
    * If a city doubles in population size, many measurable characteristics of the city, such as the number of businesses, also double in size. Around the world, from small towns to big cities, regardless of the size of city, there's always about one business establishment per 22 people, and an average of about 8 employees for each establishment.

  * **Some aspects of a city scale sub-linearly.**
    * There are often economies of scale in the infrastructure of big cities (or at least, economies of density). 
    * If a city doubles in population size, meaning it grows by 100%, parts of the supporting infrastructure tend to only grow by 85%. This is tends to be true for networks of roads, electrical cables, and municipal sewers and water pipes.

  * TODO: **Some aspects of a city scale super-linearly.**
    *
  * TODO: **Jevons paradox**
    * as **X** gets faster (and cheaper), people use more **X** [^wiki_jevons]
  * TODO: **induced demand**
    * if you add lanes to a freeway, it leads to more trips, not faster trips [^wiki_induced_demand]










## <a name="glossary"></a><span class="chapter">Glossary</span>

* **Architectural, Engineering and Construction (AEC)**
  * the entire industry of companies and people who build structures
  
* **Building Information Modeling (BIM)**
  * TODO: ???
  
* **charter city**
  * a special jurisdiction with a blank slate in commercial law, to allow for the adoption of new practices in areas such as a business registration, labor law, tax administration, and commercial dispute resolution
  * _typically built on greenfield sites to avoid the challenges of implementing such a wide array of reforms in an existing polity_
  * _typically privately financed_
  * see: special economic zone

* **co-design**
  * an design approach where stakeholders and end users are partners in the design process 

* **Community Land Trust (CLT)**
  * A nonprofit organization that owns land and sells or rents housing units (or retail or office space) built on the land, usually with the goal of providing affordable housing. A household typically leases a unit for a 99-year term, rather than buying a house outright, or may buy a house outright but leases the land that the house built on. Members elect a board so that the CLT is democratically self-governing. When a member sells a unit, the CLT may collect a cut of the sales price (in practice, as high as 75%), which it can use to subside purchases for new homeowners. [^schneider_2019-04-29]

* **curb-cut effect**
  * systems designed to benefit vulnerable groups, such as the disabled, often end up benefiting all of society
  
* **effective altruism**
  * using empirical analysis to direct resources towards efforts that do the most possible good
  * _anti-malaria efforts, deworming initiatives, and direct cash transfer programs are among the interventions most widely credited with providing the most cost-effective improvement in welfare for the global poor than any other intervention_ 
  * see [GiveWell](https://www.givewell.org/)

* **Global Compact on Refugees (GCR)**
  * a 2018 United Nations draft agreement on refugees

* **Global Compact on Safe, Orderly and Regular Migration (GCM)**
  * a 2018 United Nations agreement about international migration [^wiki_gcm]

* **Housing co-op**
  * A group of households in a multi-family building, where each household owns a share of the whole building co-op and has the right to occupy a single unit, rather than owning that unit outright. An elected board makes decisions. [^schneider_2019-04-29]

* **Inclusionary Zoning (IZ)**
  * city zoning restrictions that requires (or incentivizes) private developers to private some portion of the units in a new building at a below market rate

* **induced demand**
  * if you add lanes to a freeway, it leads to more trips, not faster trips [^wiki_induced_demand]

* **isochrone map**
  * a map with concentric isochrone lines around a center location, where all the points on any given line represent places that are equally distant, in terms of travel time, from the center location [^wiki_isochrone]

* **Jevons paradox**
  * as **X** gets faster (and cheaper), people use more **X** [^wiki_jevons]

* <a name="kinematic"></a>**kinematic**
  * concerned with the motion of bodies, and their range of motion

* **land value capture**
  * TODO: ???

* **limited equity housing cooperatives**
  * TODO: ???

* <a name="glossary:long-tail"></a>**long tail**
  * TODO: ???
 
* **Marchetti constant**
  * people will commute about 30 minutes each way per day

* **New Urban Agenda (NUA)**
  * a 2016 United Nations agreement serving as a guideline for global urban development from 2016 to 2036 [^wiki_habitat_iii]

* **Refugee City**
  * a proposal for a type of Special Economic Zone (SEZ) for displaced people [^castle-miller]
  * see also: Sustainable Development Zone (SDZ)

* **Special Economic Zone (SEZ)**
  * a part of a country in which the business and trade laws are different from the rest of the country [^wiki_sez]
  * there have been SEZs since the 1950s, and there are now thousands of SEZs around the world [^mason]

* **Sustainable Development Zone (SDZ)**
  * a proposal for designated areas that are designed to promote economic development via a combination of governance and physical infrastructure, in economies composed of displaced people [^sustainable_development_zones]
  * see also: **Refugee City**

* **Tax Increment Financing (TIF)**
  * special tax districts around targeted redevelopment areas, where future tax revenues are diverted to finance infrastructure improvements or development [^schneider]

* **Urban Consolidation Center (UCC)**
  * neighborhood-level freight hubs, place around the edge of a town, where trucks or large vehicles drop off packages to be loaded into small vehicles, like electric cargo bikes, for last-mile delivery




















## <a name="source-material"></a><span class="chapter">Source material</span>

### <a name="throughput"></a>Throughput per lane (source: NACTO[^gsdg])

|---
| Throughput | Width | Mode 
|-:|-:|:-
| people per hour
| 600 to 1,600 | one lane, **3 meters** wide | **private motor vehicles**
| 1,000 to 2,800 | one lane, **3 meters** wide | **mixed traffic** with frequent buses
| 6,500 to 7,500 | one lane, **3 meters** wide | two-way protected **bikeway**
| 4,000 to 8,000 | one lane, **3 meters** wide | dedicated **transit lanes**
| 8,000 to 9,000 | one lane, **3 meters** wide | **sidewalk**
| 10,000 to 25,000 | one lane, **3 meters** wide | on-street **transitway**, **bus** or **rail**

### <a name="throughput"></a>Throughput per lane (source: Bertaud[^bertaud])

|---
| Throughput | Vehicle type
|-:|:-
| passengers per hour per lane<br>at about 15 km/h
| 1,000 | **Bus, M1**: 5 minutes headway
| 1,600 | **cars**
| 2,600 | **Bus 4 routes**: 1 minute 48 seconds headway
| 2,800 | **motorcycles**
| 5,500 | **bicycles** on entire lane width
|---


### <a name="throughput"></a>Width per 10,000 throughput (source: NACTO[^nacto])

|---
| Throughput | Width | Mode 
|-:|-:|:-
| people per hour
| 10,000 | one lane, **12' to 15'** wide | **sidewalk**
| 10,000 | one lane, **12' to 15'** wide | **protected bike lane** 
| 10,000 | two lanes, totaling about **23'** wide | **bus-only lanes**, with 80 buses per lane per hour
| 10,000 | 13 lanes of conventional arterial, at about **156'** wide |**mostly cars**, with 800 vehicles per lane per hour
|---




### <a name="growth"></a>Global urban growth

"Half of the urban area that will be needed [by 2050] hasn't been built yet."[^growth]

"Over the next 40 years, the **newly built floor area** in the world is **expected to double**."[^watts]

"We're going to develop more urban area in the next 100 years than currently exists on Earth"[^growth] &mdash; Paul Romer, Nobel prize-winning economist, New York University.

"The amount of floorspace in buildings around the world—currently about **2.5 trillion square feet**—is set to **double by 2060**" &mdash; Brian Bienkowski [^bienkowski]

It is estimated that **by 2050**:
* about **2.5 billion additional people** will live in cities (vs. 2019), with 90% of the uptake in Asia and Africa[^growth]
* **68% of the world's population** will be living in cities (vs. 55% in 2018)[^growth][^mason]
* about **200 million climate migrants** will settle in new locations. (Forecasts vary from 25 million to 1 billion.)[^migrants]
* **400 million people in India** will migrate to cities[^sharma]
* the **African population will double** from 1.3 billion today to over **2.5 billion** [^forbes]
* there will be at least **nine African "megacities" of 10 million people or more** (and more than two dozen African cities of 5 million or more, about the size of metropolitan Washington), but currently 60 percent of Africa’s city dwellers live in slums [^bloomberg]
* one-third of all of the French Polynesian islands will be submerged[^fast-company]

> "This will be by far the largest migration of human beings to have ever taken place on the planet ... The resulting challenges to the availability of energy and resources and the enormous stress on the social fabric across the globe are mind-boggling ... and the timescales to address them are very short."[^scale] &mdash; Geoffrey West

> "The UN estimates that each year cities across the world will gain more than 72 million new residents."[^lutter]

> "averaged over the next thirty-five years, about a million and a half people will be urbanized each week ... the equivalent of another New York metropolitan area [every two months]"[^scale]

> **120 new cities** are currently being built, **in 40 countries**[^haas]

> "China ... is on a fast track to build up to **three hundred new cities** each in excess of a million people over the next twenty to twenty-five years. ...  At the present rate it will be moving the equivalent of the entire U.S. population (more than 300 million people) to cities in the next twenty to twenty-five years."[^scale]

> "India, for example, will be home to 7 cities with populations greater than 10 million residents by 2050."[^lutter]

> "projections show that Kinshasa, the capital of the Democratic Republic of Congo, will reach 35 million residents by 2050."[^lutter]



### <a name="california"></a>California urban growth

In California alone, "to satisfy pent-up demand and meet the needs of a growing population, California needs to build 3.5 million homes by 2025."[^mckinsey]

> "Broadly speaking, there is no solution to the California housing crisis without the construction of millions of new houses," said David Garcia, policy director for the Terner Center for Housing Innovation at the University of California, Berkeley.[^buhayar]

> "The infrastructure here is really tapped," Zuckerberg said Thursday. "Housing prices are way up. Traffic is bad." He added that while Facebook is trying to do what it can to help with what he called the region’s policy challenges, "at this point we’re primarily growing outside of the Bay Area." ... The CEO said he prefers big hubs where Facebook engineering teams could be around one another, and that he doesn’t want to have a lot of small offices around the world, except for where sales teams need to be in the markets they’re serving.[^sumagaysay]

> "58 of the 89 biggest — with headquarters of 100,000 square feet and above — tech and life science companies based in the Bay Area have leased 30.4 million square feet of office space in other U.S. cities since January 2010"[^sumagaysay]



### <a name="refugees"></a>Refugee migration

"An estimated 2.4 billion people–40% of the world’s population–live in a coastal region and will likely be impacted by rising sea levels as a result of climate change."[^fast-company]

As of 2018, **70 million people** were currently displaced by war, persecution and conflict. Of the total, 51 million were Internally Displaced People (IDPs), and 26 million were refugees (including **13 million refugee children**). Most refugees live in towns and cities, not rural areas or refugee camps. Nearly 4 in every 5 refugees are in displacement situations that have lasted for at least five years.[^displaced]

> "Indonesia has already announced a $34 billion plan to move its sinking, flood-prone 30-million-person capital to higher ground"[^shepard]

> "There are billions of people living on coastlines that are going to be flooded. It’s going to be worse and worse and worse year by year and they are going to have to move eventually, and where are they going to move to? ... we're going to have to deal with that on a large scale" &mdash Dr. Tom Goreau, president of the Global Coral Reef Alliance.[^shepard]

> "it has been estimated that it’s going to cost the USA alone around $400 billion over the next two decades in sea level rise damage control"[^shepard]



### <a name="precident"></a>"New city" greenfield growth

More than **120 new cities** are currently being built in 40 nations around the world[^growth], and 11,000 new buildings are built every day, meaning **4 million new buildings a year** [^metabuild].

  * **Nkwashi**, in Zambia, being built by Thebe Investment Management, is expected to house up to 100,000 people.[^mason]
  * **Tatu City**, in Kenya, being built by Rendeavour, is planned for 150,000 residents.[^mason]
  * **Forest City**, in Malaysia (700,000 residents) 
  * **Enyimba Economic City**, in Nigeria (1.5 million residents)
  * and more than 100 others...

> "Neom is best described as a $500 billion ... plan for a 10,000 square mile area"[^lutter]

> "New Cairo, ... when completed, it could house as many as 5 million residents"[^lutter]

> "Forest City is a $100 billion new city development which will house 700,000 residents when completed. Forest city is a 5600-acre development."[^lutter]



### <a name="cost"></a>Greenfield development vs. retrofitting

> "when planned, built, and governed well, cities can be massive agents of positive change," ... "They can be catalysts for inclusion and powerhouses of equitable economic growth. They can help us protect the environment and limit climate change. That is why we need a new vision for urbanization." &mdash; UN Secretary-General Ban Ki-moon [^totaro]

> "Our biggest urban problems today—growing inequality, rampant gentrification, housing unaffordability, and increasing segregation—all have roots in the staggering cost of urban land."[^manhattan]




### <a name="funding"></a>Funding for new cities

> "The money being thrown at new cities is staggering. 
> Saudi Arabia's King Abdullah Economic City comes at a price tag of **$100bn** (£78bn), 
> while the country’s Neom megalopolis is slated to cost five times that. 
> Malaysia's Forest City had its price initially pegged at **$100bn**, 
> while Ordos Kangbashi cost a hulking **$161bn**. Adding up the costs of 
> more than 120 new cities around the world means a mountain of investment 
> that can be measured in the **trillions of dollars**."[^growth]
> &mdash; Wade Shepard, author and columnist

> "An estimated $100 billion is being invested in new city projects across Africa; [the city of] Diamniadio alone will cost the Senegalese government an estimated $2 billion."[^haas]

> "Google pledged $1 billion to help create 15,000 homes in California."[^gopal]

> "Apple commits $2.5 billion to address California’s housing crisis and homelessness issues"[^perez]

> "South Sudan’s First Vice-President Taban Deng Gai said the government is working on a master plan for the proposed new capital city of Ramciel that will cost the nation 10 billion US dollars."[^tamazuj]

In 2019, U.S. Presidential candidate Andrew Yang called for **$40 billion** in subsidies, grants, and loans for people in coastal communities who want to either move inland or elevate their homes.[^yang]

### Large private-sector projects

In the past, the truly large-scale new developments have all been done by governments, at least up to now. But until recently that was true for space exploration too. Times are changing.

The global banking and investment system is taking on larger private projects now, computers and the internet enable cheaper and faster R&D, recruiting, project management, etc. Global GDP gets bigger every year, and the world takes on new and bigger projects, both public and private.

Perhaps in the coming decades we'll see increasingly large private-sector real-estate developments. Or, in the public sector, perhaps we'll see some central planning efforts that are looking for big, cost-effective, high-impact solutions to giant housing shortages.

In recent decades we have begun to see the private sector take on very large scale projects, without government funding.

City Center, in Las Vegas, Nevada, is a good example
  * 17 million square feet of mixed use space
  * built in 4 years (2006 to 2010)
  * 100% privately financed, at a cost of **$11 billion** <sup>[citation needed]</sup>

Banks, real estate developers, and the construction industry are now operating at a level where they can coordinate the successful delivery of very large projects.

In the 2020s and 2030s, is will not be crazy to propose a $20 billion privately funded construction project. The project just needs to pencil out well, be low risk, and meet the needs of customers.

### Public-sector funding mechanisms

There are established public-sector mechanisms for funding development projects, such as Tax Increment Financing (TIF).

> "Portland, Oregon, currently dedicates about 40 percent of its TIF revenues to affordable housing. Over nine years, the program generated nearly **a quarter of a billion dollars for affordable housing**..."[^schneider]

> "The $6 billion Lincoln Yards development in Chicago ... stands to receive **$1.3 billion in TIF funding**"[^schneider]









### <a name="notes"></a>Author's notes to self

  * Left-over [transportation](transportation) notes
  * Left-over [notes & quotes](remainder)
  * Work-in-progress towards a [3d city demo](demo)
  * List of [architectural terms](architecture)

#### <a name="size"></a>Size & density

  * **Bigger may not be better.** Big cities, with more people, have more destinations to go to, and have a wider variety of destinatations. But, if there's too much congestion, it may take too long to get to the other side of town, so that limits your kinematic range. Your range doesn't cover the whole city, just the region of the city that's within 30 minutes of you.
  * **Denser may not be better.** New York is much denser than Los Angeles, so there are more destinations per square mile in New York than there are in Los Angeles. But it takes longer to travel 10 miles in New York than in does in Los Angeles, so Los Angeles actually has a larger kinematic range than New York.









### <a name="references"></a><span class="chapter">References</span>


<!-- References, Chapter 1 -->

[^bertaud]: _[Order without Design](https://mitpress.mit.edu/books/order-without-design): How Markets Shape Cities_, by Alain Bertaud

[^gsdg]: ["Global Street Design Guide"](https://nacto.org/publication/global-street-design-guide/). _National Association of City Transportation Officials (NACTO)_.

[^nacto]: ["Blueprint for Autonomous Urbanism"](https://nacto.org/publication/bau2/), Second Edition. _National Association of City Transportation Officials (NACTO)_.

[^nycdot]: ["New York City Mobility Report"](http://www.nyc.gov/html/dot/downloads/pdf/mobility-report-2018-screen-optimized.pdf), June 2018. _NYC Department of Transportation_.

[^speed-limits]: ["Manhattan Speed Limits"](https://www1.nyc.gov/html/dot/downloads/pdf/current-pre-vision-zero-speed-limit-maps.pdf).  _NYC Department of Transportation_.










<!-- References, Chapter 2 -->

[^google_eie]: [Environmental Insights Explorer](https://insights.sustainability.google/places/ChIJIQBpAG2ahYAR_6128GcTUEo/transportation). _Google_. 2018.

[^growth]: ["Should we build cities from scratch?"](https://www.theguardian.com/cities/2019/jul/10/should-we-build-cities-from-scratch). _The Guardian_. 10 July 2019.

[^scale]: [_Scale_](https://www.penguinrandomhouse.com/books/314049/scale-by-geoffrey-west/), by Geoffrey West. 2018.









<!-- References, Chapter 4 -->

[^bienkowski]: ["We're building the equivalent of Paris every week. That's a problem."](https://www.dailyclimate.org/building-industry-climate-change-carbon-footprint-2516418302.html). Brian Bienkowski, _The Daily Climate_. 11 Dec 2017.

[^bloomberg]: ["Africa’s Cities Are About to Boom – and Maybe Explode"](https://www.bloomberg.com/opinion/articles/2019-07-25/africa-s-cities-are-about-to-boom-and-maybe-explode). _Bloomberg_. 25 July 2019.

[^buhayar]: ["How California Became America’s Housing Market Nightmare"](https://www.bloomberg.com/graphics/2019-california-housing-crisis/). Noah Buhayar and Christopher Cannon, _Bloomberg_. 6 November 2019

[^caspar]: ["The Future of Greenfield Cities"](https://newcities.org/the-big-picture-the-future-of-greenfield-cities/). _NewCities_. 23 July 2019.

[^displaced]: ["Worldwide displacement tops 70 million, UN Refugee Chief urges greater solidarity in response"](https://www.unhcr.org/uk/news/press/2019/6/5d03b22b4/worldwide-displacement-tops-70-million-un-refugee-chief-urges-greater-solidarity.html). _UNHCR: The UN Refugee Agency_. 19 June 2019.

[^fast-company]: ["Floating cities once seemed like sci-fi. Now the UN is getting on board"](https://www.fastcompany.com/90329294/floating-cities-once-seemed-like-sci-fi-now-the-un-is-getting-on-board). _Fast Company_. 4 April 2019.

[^fitzsimmons]: ["M.T.A. Pledges $5 Billion for Subway Elevators. Guess How Many."](https://www.nytimes.com/2019/10/07/nyregion/mta-nyc-subway-elevators.html). Emma G. Fitzsimmons & Rebecca Liebson, _New York Times_. 7 October 2019.

[^forbes]: ["The Power Of Purpose: Unlocking Africa's $10 Trillion Opportunity In Housing"](https://www.forbes.com/sites/afdhelaziz/2019/09/12/the-power-of-purpose-unlocking-africas-10-trillion-opportunity-in-housing/#1e1fa3b714a0). _Forbes_. 12 September 2019.

[^gopal]: ["Affordable Housing"](https://www.bloomberg.com/quicktake/affordable-housing). Prashant Gopal and Rob Urban, _Bloomberg_. 21 Oct 2019.

[^growth]: ["Should we build cities from scratch?"](https://www.theguardian.com/cities/2019/jul/10/should-we-build-cities-from-scratch). _The Guardian_. 10 July 2019.

[^haas]: ["African countries keep building new cities to meet rapid urbanization even if people won’t live in them"](https://qz.com/africa/1740068/african-countries-keep-building-cities-to-meet-rapid-urbanization/). Astrid R.N. Haas, _International Growth Centre_. 31 October 2019.

[^lutter]: ["Exponents Magazine: A Beginner's Guide to Building New Cities"](https://www.chartercitiesinstitute.org/post/a-beginners-guide-to-building-new-cities?utm_source=Charter+Cities+Institute&utm_campaign=c1b3cc2a39-EMAIL_CAMPAIGN_2019_11_04_11_59&utm_medium=email&utm_term=0_fccc97d8cc-c1b3cc2a39-223014821). Dr. Mark Lutter, _Charter Cities Institute_. 9 October 2019.

[^manhattan]: ["What's Manhattan's Land Worth? Try 'Canada's Entire GDP'"](https://www.citylab.com/life/2018/04/what-manhattans-land-is-worth/558776/). Richard Florida, _CityLab_. 24 April 2018.

[^mason]: ["The Case for Charter Cities Within the Effective Altruist Framework"](https://assets.website-files.com/5d253237e31f051057dc0a2b/5d88effe42420361c5e0c3c2_The%20Case%20for%20Charter%20Cities%20Within%20the%20Effective%20Altruist%20Framework.pdf). Jeffrey Mason, _Charter Cities Institute_. Sept 2019.

[^mckinsey]: ["A Tool Kit to Close California's Housing Gap: 3.5 Million Homes by 2025"](https://www.mckinsey.com/~/media/McKinsey/Featured%20Insights/Urbanization/Closing%20Californias%20housing%20gap/Closing-Californias-housing-gap-Full-report.ashx). _McKinsey & Company_. October 2016

[^metabuild]: ["urbAIn – AI, Cities, and Climate Change"](https://www.metabuild.io/urbain-ai-cities-and-climate-change/). _Metabuild.io_. 15 June 2019.

[^migrants]: ["Migration, Environment and Climate Change: Assessing the Evidence"](https://publications.iom.int/system/files/pdf/migration_and_environment.pdf). (PDF) _International Organization for Migration_. 2009.

[^perez]: ["Apple commits $2.5 billion to address California’s housing crisis and homelessness issues"](https://techcrunch.com/2019/11/04/apple-commits-2-5-billion-to-address-californias-housing-crisis-and-homelessness-issues/). Sarah Perez, _TechCrunch_. 4 November 2019.

[^scale]: [_Scale_](https://www.penguinrandomhouse.com/books/314049/scale-by-geoffrey-west/), by Geoffrey West. 2018.

[^schneider]: ["CityLab University: Tax Increment Financing"](https://www.citylab.com/equity/2019/10/tax-increment-financing-explained-tif-economic-development/597313/). Benjamin Schneider, _CityLab_. 24 Oct 2019.

[^sharma]: ["Greenfield Smart Cities Shaping the Future of India"](https://newcities.org/the-big-picture-greenfield-smart-cities-shaping-future-india/). _NewCities_. 23 July 2019.

[^shepard]: ["Waterworld? Floating Cities Turn Hollywood Sci-fi Into Reality As Sea Levels Rise"](https://www.forbes.com/sites/wadeshepard/2019/10/23/waterworld-floating-cities-turn-hollywood-sci-fi-into-reality-as-sea-levels-rise/#2da78d07655c). Wade Shepard, _Forbes_. 23 Oct 2019.

[^sumagaysay]: ["Bay Area housing, traffic have Facebook looking elsewhere for expansion"](https://www.mercurynews.com/2019/10/04/bay-area-housing-traffic-have-facebook-looking-elsewhere-for-expansion/). Levi Sumagaysay, _Bay Area News Group_. 4 October 2019.

[^tamazuj]: ["Proposed Ramciel city master plan to cost 10 billion USD"](https://radiotamazuj.org/en/news/article/proposed-ramciel-city-master-plan-to-cost-10-billion-usd). _Radio Tamazuj_. 30 October 2019.

[^totaro]: ["Slumscapes: How the world's five biggest slums are shaping their futures"](https://uk.reuters.com/article/uk-slums-united-nations-world-insight-idUKKBN12H1GK). Paola Totaro, _Reuters_. 17 October 2016.

[^watts]: ["Concrete: the most destructive material on Earth"](https://www.theguardian.com/cities/2019/feb/25/concrete-the-most-destructive-material-on-earth). Jonathan Watts, _The Guardian_. 25 Feb 2019 

[^yang]: ["Andrew Yang’s plan to tackle climate change, explained"](https://www.vox.com/future-perfect/2019/8/26/20833263/andrew-yang-climate-plan). _Vox.com_. 26 August 2019.







<!-- References, Glossary -->

[^wiki_gcm]: ["Global Compact for Migration"](https://en.wikipedia.org/wiki/Global_Compact_for_Migration). _Wikipedia_.

[^wiki_induced_demand]: ["Induced demand"](https://en.wikipedia.org/wiki/Induced_demand). _Wikipedia_.

[^wiki_isochrone]: ["Isochrone map"](https://en.wikipedia.org/wiki/Isochrone_map). _Wikipedia_.

[^wiki_jevons]: ["Jevons paradox"](https://en.wikipedia.org/wiki/Jevons_paradox). _Wikipedia_.

[^wiki_habitat_iii]: ["Habitat III: New Urban Agenda"](https://en.wikipedia.org/wiki/Habitat_III#New_Urban_Agenda). _Wikipedia_.

[^castle-miller]: ["The Law and Policy of Refugee Cities: Special Economic Zones for Migrants"](https://refugeecities.files.wordpress.com/2018/07/refugee-cities-law-review-article.pdf). Michael Castle-Miller, _Politas Consulting_. July 2018.

[^schneider_2019-04-29]: ["CityLab University: Shared-Equity Homeownership"](https://www.citylab.com/equity/2019/04/home-ownership-ideas-housing-co-ops-shared-equity-land-trust/585658/). Benjamin Schneider, _CityLab_. 29 April 2019.

[^wiki_sez]: ["Special economic zone"](https://en.wikipedia.org/wiki/Special_economic_zone). _Wikipedia_.

[^mason]: ["The Case for Charter Cities Within the Effective Altruist Framework"](https://assets.website-files.com/5d253237e31f051057dc0a2b/5d88effe42420361c5e0c3c2_The%20Case%20for%20Charter%20Cities%20Within%20the%20Effective%20Altruist%20Framework.pdf). Jeffrey Mason, _Charter Cities Institute_. Sept 2019.

[^sustainable_development_zones]: ["Sustainable Development Zones"](https://refugeecities.files.wordpress.com/2018/07/sdz-concept-proposal-071118-final.pdf). July 2018.

[^schneider]: ["CityLab University: Tax Increment Financing"](https://www.citylab.com/equity/2019/10/tax-increment-financing-explained-tif-economic-development/597313/). Benjamin Schneider, _CityLab_. 24 Oct 2019.










<!-- References, ??? -->

[^growth]: ["Should we build cities from scratch?"](https://www.theguardian.com/cities/2019/jul/10/should-we-build-cities-from-scratch). _The Guardian_. 10 July 2019.

[^watts]: ["Concrete: the most destructive material on Earth"](https://www.theguardian.com/cities/2019/feb/25/concrete-the-most-destructive-material-on-earth). Jonathan Watts, _The Guardian_. 25 Feb 2019 

[^bienkowski]: ["We're building the equivalent of Paris every week. That's a problem."](https://www.dailyclimate.org/building-industry-climate-change-carbon-footprint-2516418302.html). Brian Bienkowski, _The Daily Climate_. 11 Dec 2017.

