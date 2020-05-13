---
permalink: /cities/
---
# <a name="0"></a>Impossible Cities

This paper outlines a summer 2020 design proposal for building car-free cities.

1. **Streets designed for mobility &mdash; better design choices** 
  * This proposal hinges on a re-design of what a city street looks like, to try to get less congestion, twice the average speed, and twice the total throughput (compared to, say, Manhattan New York). See <a href="#1">chapter 1</a>.
2. **Mobility for prosperity, not for speed**
  * The main goal of the new design is to increase urban mobility. However, non-intuitively, the benefit is **not** faster commutes, but is instead higher wages & more social opportunities, as well as higher land values & better investment return rates. See <a href="#2">chapter 2</a>.
3. **Beyond mobility &mdash; better cities & better outcomes**
  * The main goal is better mobility, but the design has a variety of other potential upsides. Cities like this should be greener, cleaner, fairer, safer, simpler, and more reliable & resilient. See <a href="#3">chapter 3</a>.
4. **This matters now**
  * This is an important area for study & discussion right now, because there's about to be a huge influx of urban population, and a huge increase in urban construction. The construction of buildings will happen no matter what, so it would be good to try to do it in conjunction with the construction of modern transportation networks, rather than just repeating what was done in past decades. See <a href="#4">chapter 4</a>.
5. **This requires better funding models & better value capture agreements**
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

.orange {
  color: #df4911;
}

</style>





















<div id="contents-title">
  <div style="float:right;">Contents</div>
  <div id="contents-entries">
    <p>&nbsp;</p>
    <div>
      <details>
        <summary><a href="#0">Impossible Cities</a></summary>
        <ul>
          <li><a href="#0">Summary</a></li>
        </ul>
      </details>
    </div>
    <div>
      <details>
        <summary><a href="#1">1. Streets designed for mobility</a></summary>
        <ul>
          <li><a href="#comparison">2nd Ave vs. Impossible Street</a></li>
          <li><a href="#intersection">Impossible intersection design</a></li>
          <li><a href="#bike-sized">Bike-sized vehicles</a></li>
          <li><a href="#freight">Freight</a></li>
          <li><a href="#emergency-vehicles">Emergency vehicles</a></li>
        </ul>
      </details>
    </div>
    <div>
      <details>
        <summary><a href="#2">2. Mobility for prosperity, not for speed</a></summary>
        <ul>
          <li><a href="#kinematic_range">Kinematic range</a></li>
          <li><a href="#why-does-it-matter">Why does kinematic range matter?</a></li>
          <li><a href="#windfall">Kinematic windfall</a></li>
          <li><a href="#density">Density & kinematic range</a></li>
          <li><a href="#existing-cities">The kinematics of existing cities</a></li>
          <li><a href="#impossible">The "Impossible City" design proposal</a></li>
       </ul>
      </details>
    </div>
    <div>
      <details>
        <summary><a href="#3">3. Bonus features beyond mobility</a></summary>
        <ul>
          <li><a href="#affordability">Affordability</a></li>
          <li><a href="#convenience">Conviviality & convenience</a></li>
          <li><a href="#durability">Durability, reliability & resilience</a></li>
          <li><a href="#economic-prosperity">Economic prosperity</a></li>
          <li><a href="#freedom">Freedom, independence & agency</a></li>
          <li><a href="#sustainability">Green sustainability</a></li>
          <li><a href="#health">Health & safety</a></li>
        </ul>
      </details>
    </div>
    <div>
      <details>
        <summary><a href="#4">4. Why this matters now</a></summary>
        <ul>
          <li><a href="#population-boom">Urban population boom</a></li>
          <li><a href="#construction-boom">Urban construction boom</a></li>
          <li><a href="#megacities">"Megacity" urban agglomerations</a></li>
          <li><a href="#kinematic-lag">Kinematic lag</a></li>
          <li><a href="#lost-opportunities">Lost opportunities</a></li>
          <li><a href="#current-opportunities">Current opportunities</a></li>
        </ul>
      </details>
    </div>
    <div>
      <details>
        <summary><a href="#5">5. Why this is impossible</a></summary>
        <ul>
          <li><a href="#location">Location problems</a></li>
          <li><a href="#network-effect">Network effect problems</a></li>
          <li><a href="#cost">Cost problems</a></li>
          <li><a href="#bootstrapping">Bootstrapping problems</a></li>
          <li><a href="#land-value-capture-problems">Land value capture problems</a></li>
          <li><a href="#summary">Summary</a></li>
        </ul>
      </details>
    </div>
    <div>
      <details>
        <summary><a href="#faq-etc">FAQ, etc.</a></summary>
        <ul>
          <li><a href="#faq">FAQ</a></li>
          <li><a href="#rules-of-thumb">Rules of thumb</a></li>
          <li><a href="#effective-altruism">Effective altruism</a></li>
        </ul>
      </details>
    </div>
    <div>
      <details>
        <summary><a href="#appendixes">Appendixes</a></summary>
        <ul>
          <li><a href="#further-reading">Books and software</a></li>
          <li><a href="#glossary">Glossary</a></li>
          <li><a href="#hypothetical-locations">Hypothetical locations</a></li>
          <li><a href="#design-summary">Impossible City design summary</a></li>
          <li><a href="#source-material">Source material</a></li>
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
  | **sidewalks**    | two 20-foot wide sidewalks | two 15-foot wide sidewalks at ground level <br> two 25-foot wide "[High Line](#glossary:high-line)"-style greenways with footpaths
  | **streets**      | one 60-foot wide open-air street      | two 30-foot wide enclosed streets elevated on 2nd floor
  | **lanes**        | six conventional vehicle lanes<br>_all one-way southbound_<br>_each lane 10 feet wide_ | eight bicycle lanes<br>_4 northbound & 4 southbound_<br>_each lane 6 feet wide, plus two shoulders, each 3 feet wide_
  | **vehicles**     | 1 bus-only lane<br> 4 lanes for cars, trucks, taxis, etc. <br> 1 lane parking & curbside loading | 8 lanes for bicycles and <a href="#bike-sized">bike-sized vehicles</a>
  | **cross-streets** | about 20 per mile | 8 per mile
  | **traffic lights** | about 20 per mile | none
  | **intersections** | at-grade conventional intersections | grade-separated intersections
  | **trees** | about 150 per mile | about 200 per mile
  | **speed limits**<br>as posted | 25 mph[^speed-limits] | 18 mph 
  | **actual speed**<br>average | 7.1 mph for cars[^nycdot]<sup>,</sup>[^haag] <br> 7.5 mph for buses[^nycdot] | 15 mph 
  | **vehicle<br>throughput** | 1 bus lane at about 6,000 people per hour (+/- 2,000)<br> 4 car lanes at about 1,000 people per hour each (+/- 400)<br>1 parking & delivery lane at 0 people per hour<br>**total:** about 11,000 people per hour | 8 bike lanes at about 3,500 people per hour per bike lane each (+/- 250 per hour)<br>**total:** about 28,000 people per hour
  | **sidewalk<br>throughput** | about 10,000 people per hour | about 10,000 people per hour
  | **bottom line** | less than half as many people as Impossible City design<br>each moving half as fast | twice as many people as Manhattan<br>each moving twice as fast
  |  | <a name="costs"></a><span class="h3">Costs</span> | 
  | **traffic fatalities** | 23 fatalities per million people per year | 1 fatality per million per year
  | **CO2 footprint<br>for transportation**<br>kg per person per year | 1,000 kg | 1 kg
  | **cost of public transit**<br>annual dollars per capita | $360 in fares paid by riders<br>$720 in city funded transit subsidies<br>**$1,080** total | $0
  | **private vehicle costs**<br>annual dollars per capita | $1,000<br>_mostly for cars_<br>_about 1 car per 10 people_ | $1,000<br>_mostly for bicycles, e-bikes, mopeds, scooters, etc._<br>_about 1 vehicle per person_
  | **air quality** | good | _really_ good
  | **noise levels** | noisier | quieter<br><span class="minor">(see [noise](#noise))</span>
  |  | <a name="costs"></a><span class="h3">Real estate</span> | 
  | **floorspace** | no real estate floorspace in street | 680,000 square feet of floor space per mile


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


  |---
  |  | <span class="h3">Examples</span> | 
  |:-:|:-|:-
  |  | <span class="minor">(The copyright to these pictures belongs to their respective owners. The pictures are used here under fair use, and are not included as part of the [Creative Commons Zero v1.0 Universal](https://raw.githubusercontent.com/nicky-nym/nicky-nym.github.io/master/LICENSE.txt) license/waiver that applies to the rest of this paper.)</span>  | 
  | **bicycles** | <a href="https://www.planetizen.com/files/styles/news_header_sm/public/images/BikeCommute.jpg"><img src="../images/thumbnails/BikeCommute.jpg" alt="bike commuter" height="100"/></a> <a href="https://kanwalkwilltravel.com/img/d695ee7c345f982116b270d93e17ede7.png"><img src="../images/thumbnails/d695ee7c345f982116b270d93e17ede7.jpg" alt="bmx bike" height="100"/></a>
  | **family bicycles** | <a href="https://cupofjo.com/wp-content/uploads/2015/09/cup-of-jo-bikes-8-3.jpg"><img src="../images/thumbnails/cup-of-jo-bikes-8-3.jpg" alt="family bicycle" height="100"/></a> <a href="https://www.macheesmo.com/wp-content/uploads/2018/09/cargo-bike1.jpg"><img src="../images/thumbnails/cargo-bike1.jpg" alt="family bicycle" height="100"/></a> <a href="https://i.pinimg.com/originals/32/b0/ec/32b0ec61eaf544b3b482dc7faa9036f5.jpg"><img src="../images/thumbnails/32b0ec61eaf544b3b482dc7faa9036f5.jpg" alt="family bicycle" height="100"/></a> <a href="https://momentummag.com/wp-content/uploads/2016/05/taga2main-1.jpg"><img src="../images/thumbnails/taga2main-1.jpg" alt="family bicycle" height="100"/></a>
  | **folding bicycles**<br>**&**<br>**compact hybrids** | <a href="https://theawesomer.com/photos/2019/04/halfbike_3_5.jpg"><img src="../images/thumbnails/halfbike_3_5.jpg" alt="halfbike" height="100"/></a> <a href="https://cdn.thisiswhyimbroke.com/images/halfbike-half-bike-640x534.jpg"><img src="../images/thumbnails/halfbike-half-bike-640x534.jpg" alt="halfbike" height="100"/></a> <a href="https://avialbikes.com/wp-content/uploads/2019/04/YikeBike-folding-e-bike_2-1024x700.jpg"><img src="../images/thumbnails/YikeBike-folding-e-bike_2-1024x700.jpg" alt="YikeBike" height="100"/></a> <a href="https://gocycle.com/wp-content/uploads/2019/09/gxi-design0-mob-compressor.jpg"><img src="../images/thumbnails/gxi-design0-mob-compressor.jpg" alt="Gocycle" height="100"/></a> <a href="https://cleantechnica.com/files/2019/01/jack-rabbit-mobility-ces-2019-las-vegas-1.jpg"><img src="../images/thumbnails/jack-rabbit-mobility-ces-2019-las-vegas-1.jpg" alt="Jack Rabbit" height="100"/></a>
  | **electric bicycles** | <a href="https://sandiegoflyrides.com/wp-content/uploads/2018/01/18_Delite_25_black_outdoor-1024x683.jpg"><img src="../images/thumbnails/18_Delite_25_black_outdoor-1024x683.jpg" alt="Riese & Muller Delite" height="100"/></a> <a href="https://sandiegoflyrides.com/wp-content/uploads/2018/01/18_Roadster_1-1024x682.jpg"><img src="../images/thumbnails/18_Roadster_1-1024x682.jpg" alt="Riese & Muller Roadster" height="100"/></a>
  | **mopeds & scooters**<br>(electric) | <a href="https://assets.bwbx.io/images/users/iqjWHBFdfxIU/i.gOCVej_0Rw/v0/1000x-1.jpg"><img src="../images/thumbnails/1000x-1.jpg" alt="Bird scooter" height="100"/></a> <a href="https://static.standard.co.uk/s3fs-public/thumbnails/image/2020/01/09/09/escooters0901a.jpg?w968"><img src="../images/thumbnails/escooters0901a.jpg" alt="electric scooter" height="100"/></a> <a href="https://static.timesofisrael.com/www/uploads/2019/07/000_1H28W6-640x400.jpg"><img src="../images/thumbnails/000_1H28W6-640x400.jpg" alt="two-person scooter" height="100"/></a> <a href="https://smartelectricscooters.com/wp-content/uploads/2018/08/Best-Electric-Scooter-for-Adults-300x300.jpg"><img src="../images/thumbnails/Best-Electric-Scooter-for-Adults-300x300.jpg" alt="sitting scooter" height="100"/></a> <a href="https://i.pinimg.com/originals/c3/21/9f/c3219fa308b64ff0599bf01164bfb402.jpg"><img src="../images/thumbnails/c3219fa308b64ff0599bf01164bfb402.jpg" alt="Bird sitting scooter" height="100"/></a>
  | **passenger trikes** | <a href="https://www.e-scooter.co/i/20/b7/f4/d206a1db125ad4834b79dca399.jpg"><img src="../images/thumbnails/d206a1db125ad4834b79dca399.jpg" alt="Doohan iTango" height="100"/></a> <a href="https://cgmood.com/storage/previews/09-2019/6622/6622-13707.jpeg"><img src="../images/thumbnails/6622-13707.jpeg" alt="Doohan iTango" height="100"/></a> <a href="https://www.heradas.lt/image/image5c139ee727d78.png"><img src="../images/thumbnails/image5c139ee727d78.jpg" alt="Doohan iTango" height="100"/></a> <a href="https://i0.wp.com/www.greenoptimistic.com/wp-content/uploads/2014/07/Toyota-i-Road-0001-537x358.jpg?fit=537%2C358&ssl=1"><img src="../images/thumbnails/Toyota-i-Road-0001-537x358.jpg" alt="Toyota iRoad" height="100"/></a> <a href="https://images.hgmsites.net/lrg/2018-carver_100650884_l.jpg"><img src="../images/thumbnails/2018-carver_100650884_l.jpg" alt="Carver" height="100"/></a> <a href="https://www.e-scooter.co/i/3f/fc/1f/da2e9af5182ceea96b13bafe5a.jpg"><img src="../images/thumbnails/da2e9af5182ceea96b13bafe5a.jpg" alt="Carver" height="100"/></a> <a href="https://i.servimg.com/u/f47/15/57/88/64/dscf2510.jpg"><img src="../images/thumbnails/dscf2510.jpg" alt="Schaeffler Bio-Hybrid" height="100"/></a> <a name="cargo-trikes"></a>
  | **cargo trikes** | <a href="https://bikeportland.org/wp-content/uploads/2018/10/download-2.jpeg"><img src="../images/thumbnails/download-2.jpeg" alt="Truck Trike" height="100"/></a> <a href="https://www.amsterdam-bicycle.com/wpcms/wp-content/uploads/E-Cargo-Trike-Classic-Narrow-Pearl-Blue-Metallic-Gloss.jpg"><img src="../images/thumbnails/E-Cargo-Trike-Classic-Narrow-Pearl-Blue-Metallic-Gloss.jpg" alt="Bakfiets.nl" height="100"/></a> <a href="https://sc01.alicdn.com/kf/HTB1PDOFXEvrK1RjSszfq6xJNVXap.jpg"><img src="../images/thumbnails/HTB1PDOFXEvrK1RjSszfq6xJNVXap.jpg" alt="Ester Heavy Load Electric Assisted Cargo Trike" height="100"/></a> <a href="https://www.practicalcycle.com/wp-content/uploads/nihola_flex_open.jpg"><img src="../images/thumbnails/nihola_flex_open.jpg" alt="Nihola Flex" height="100"/></a> <a href="https://media.treehugger.com/assets/images/2017/04/17814216_280991905658092_1554833526111068713_o.jpg.860x0_q70_crop-scale.jpg"><img src="../images/thumbnails/17814216_280991905658092_1554833526111068713_o.jpg.860x0_q70_crop-scale.jpg" alt="Sanitov's movE" height="100"/></a> <a href="https://electricbikereview.com/wp-content/assets/2019/08/2019-rad-power-bikes-radburro-stock-truck-bed-1200x800-c-default.jpg"><img src="../images/thumbnails/2019-rad-power-bikes-radburro-stock-truck-bed-1200x800-c-default.jpg" alt="Rad Power Bikes RadBurro" height="100"/></a> <a name="cargo-vans"></a>
  | **cargo vans** | <a href="https://fuseid.com/wp-content/uploads/2016/05/Truck-Trike-Hero-Render-Profile-1280x600.jpg"><img src="../images/thumbnails/Truck-Trike-Hero-Render-Profile-1280x600.jpg" alt="UPS" height="100"/></a> <a href="https://s3-us-west-2.amazonaws.com/uw-s3-cdn/wp-content/uploads/sites/6/2018/10/24161707/Urban-Delivery-Solutions-Social-Media-Edit-041-still.jpg"><img src="../images/thumbnails/Urban-Delivery-Solutions-Social-Media-Edit-041-still.jpg" alt="UPS" height="100"/></a> <a href="https://www.electrive.com/wp-content/uploads/2019/12/eav-cargo-pedelec-lasten-pedelec-2019-01-min-444x222.png"><img src="../images/thumbnails/eav-cargo-pedelec-lasten-pedelec-2019-01-min-444x222.jpg" alt="eav" height="100"/></a> <a href="https://internationalfleetworld.com/wp-content/uploads/2019/09/eaVAN-350x263.jpg"><img src="../images/thumbnails/eaVAN-350x263.jpg" alt="eav" height="100"/></a> <a href="https://i1.wp.com/www.electricbike.com/wp-content/uploads/2013/11/FedExTrike2.jpg?resize=504%2C378&ssl=1"><img src="../images/thumbnails/FedExTrike2.jpg" alt="FedEx" height="100"/></a>
  | **motor-chairs<br>&<br>wheelchairs** | <a href="https://news-cdn.softpedia.com/images/news2/Meet-Speedster-the-World-s-Fastest-Wheelchair-2.jpg"><img src="../images/thumbnails/Meet-Speedster-the-World-s-Fastest-Wheelchair-2.jpg" alt="TankChair Speedster" height="100"/></a> <a href="https://www.ultimatecarpage.com/images/gallery/fos08/Toyota-i-REAL-111493.jpg"><img src="../images/thumbnails/Toyota-i-REAL-111493.jpg" alt="Toyota i-real" height="100"/></a> <a href="https://upload.wikimedia.org/wikipedia/commons/e/e7/2007_Toyota_i-Real_02.jpg"><img src="../images/thumbnails/2007_Toyota_i-Real_02.jpg" alt="Toyota i-real" height="100"/></a> 
  | **hoverboards<br>segways<br>ninebots<br>electric skateboards<br>etc.** | <a href="https://cdn.thisiswhyimbroke.com/images/segway-mini-300x250.jpg"><img src="../images/thumbnails/segway-mini-300x250.jpg" alt="Ninebot Mini Pro" height="100"/></a> <a href="https://ninebot.com.sg/wp-content/uploads/2018/03/Ninebot_ONE-S2-rider-url-1000x1000.jpg"><img src="../images/thumbnails/Ninebot_ONE-S2-rider-url-1000x1000.jpg" alt="Ninebot ONE S2" height="100"/></a> <a href="https://electrek.co/wp-content/uploads/sites/3/2019/03/DSC_1248-copy.jpg?quality=82&strip=all&w=678"><img src="../images/thumbnails/DSC_1248-copy.jpg" alt="Kiwano KO1+" height="100"/></a> <a name="delivery-robots"></a>
  | **delivery robots** | <a href="https://cdn.geekwire.com/wp-content/uploads/2019/01/amazonscout-768x600.png"><img src="../images/thumbnails/amazonscout-768x600.jpg" alt="Amazon scout" height="100"/></a> <a href="https://techcrunch.com/wp-content/uploads/2019/04/AD03.jpg?w=730&crop=1"><img src="../images/thumbnails/AD03.jpg" alt="brain OS" height="100"/></a> <a href="https://www.supermarketnews.com/sites/supermarketnews.com/files/styles/article_featured_retina/public/FedEx_SameDay_Bot_street_1.png?itok=Ml2UGf3F"><img src="../images/thumbnails/FedEx_SameDay_Bot_street_1.jpg" alt="FedEx bot" height="100"/></a> <a href="https://wdwnt-buzzy.s3.amazonaws.com/2020/01/IMG_5441.jpg"><img src="../images/thumbnails/IMG_5441.jpg" alt="R2-D2" height="100"/></a>
  |---


> No technology holds as much promise as the humble bicycle—especially 
> when we include its newfangled, electrified cousins—to solve the 
> geometry problem that is getting people short distances around a big city...
> We don't need no flying cars. Just give us a place to ride, and watch 
> e-bikes eat everything. [^alter]




### <a name="freight"></a>Freight

The Impossible City design strives for good urban mobility not just for people, but also for freight shipments and package delivery.

The design constraints for cargo mobility have a lot in common with the design constraints for human mobility, and there's considerable overlap in terms of what good solutions look like. In the Impossible City design, most packages and cargo would travel on the same elevated bikeway streets that commuters use. 

On the bikeway streets, almost all cargo and packages would be carried in narrow, bike-sized vehicles. Cargo vehicles would include human-powered [cargo trikes](#cargo-trikes), electric-assist trikes, and fully electric [cargo vans](#cargo-vans), in both 3-wheel and 4-wheel flavors. Self-driving [delivery robots](#delivery-robots) could also work well, once that technology becomes reliable and cost-effective.

Cargo trikes and cargo vans are fine for small package delivery, and for tasks involving lots of small items, such as keeping grocery stores and retail stores stocked. Even items as large as sofas and refrigerators are appropriate for small cargo vans. 

For larger items, the city needs other alternatives. The Impossible streets are intentionally designed to be large enough to accommodate objects such as standard 40-foot intermodal shipping containers, or the modular mast segments of a conventional construction site tower crane <sup>(see [video](https://www.youtube.com/watch?v=vx5Qt7_ECEE))</sup>. These wide loads would be the exception, not the rule, because they would take up two or three side-by-side lanes of the bikeway streets, which would inconvenience ordinary commuter traffic. If necessary, the bikeways are also large enough for conventional buses, panel vans, and box trucks.

  |---
  |  |  | 
  |:-:|:-|
  | **shipping container** | <a href="https://commons.wikimedia.org/wiki/File:Container_01_KMJ.jpg"><img src="../images/thumbnails/Container_01_KMJ.jpg" alt="shipping container" height="100"/></a><br><span class="minor">(Copyright [KMJ](https://de.wikipedia.org/wiki/Benutzer:KMJ), licensed under the [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) license and GNU Free Documentation License.)</span>

Some oversize items, such as heavy industrial equipment, may be too large to put in shipping containers or box trucks. These items can be transported on ground surface right-of-ways, rather than on the elevated bikeways. The Impossible City design has fewer ground surface right-of-ways, at a wider spacing, and even the ground surface right-of-ways will have a 16' vertical clearance, identical to the U.S. Interstate Highway standard 16' clearance. 


### <a name="emergency-vehicles"></a>Emergency vehicles

The Impossible streets are intentionally designed to be large enough to accommodate ordinary fire engines, ambulances, and other emergency vehicles. The city boulevards are painted with lane markings for narrow 6-foot lanes for bike-sized vehicles, but the boulevards themselves are always 4 lanes wide, plus shoulders. The bikeways have an unobstructed width of about 30 feet, and unobstructed height clearance of 14 feet. The entrance and exit ramps are single-lane, but have intentionally been designed to be wide enough for standard emergency vehicles. 

Although traditional fire engines can use the boulevards, they may not be necessary. It may be possible for the city to have a larger number of smaller fire-fighting vehicles for different sorts of cargo:
* tender vehicles for hauling water
* pump engines for pumping from sources like canals
* rescue vehicles for hauling floodlights, hydraulic rescue tools, etc.
* hazardous materials vehicles with hazmat suits, etc.

Ideally the Impossible City buildings would all be built with standpipes and fire sprinkler systems, so pump engines and tender vehicles may be less important in an impossible city, allowing the city to instead have more ambulances, hazmat vehicles and rescue vehicles.

A variety of small vehicles can be used for different types of emergency response. These types of vehicles are uncommon here in the United States, but are not a new invention, and are in use elsewhere in the world in places with narrow streets. Examples include: 
* motorcycle ambulances<sup>([link](https://en.wikipedia.org/wiki/Motorcycle_ambulance))</sup>
* nontransporting emergency medical service vehicles<sup>([link](https://en.wikipedia.org/wiki/Nontransporting_EMS_vehicle))</sup>
* compact firetrucks, like these: 
  + [Tropos/Panasonic](https://www.autoblog.com/2020/01/07/panasonic-tropos-motors-fire-truck-cargo-vehicles/)
  + [Cherry Grove](http://www.unyquefiretrucks.com/Under_The_Boardwalk_files/li_cherrygrove_5-26-2dsrear.jpg)
  + [SPV](https://www.spv-vehicle.com/company-news/civic-utility-truck/spv-recently-promotes-mini-changan-fire-truck-quick-attack-fire-truck-150.html)
  + [Foton 1500L water tank fire truck](https://www.alibaba.com/product-detail/1500L-foton-mini-fire-truck_60793504463.html)

<img src="../images/thumbnails/Foton.jpg" alt="Foton water tank fire truck" height="200"/>











<div class="hr"><a name="2"></a></div>

## <span class="chapter">_Chapter 2_ &mdash; Mobility for prosperity, not for speed</span>

The [impossible streets](#1) & intersections are designed to yield **faster travel times** and **higher throughput**, compared to conventional streets in cities like San Francisco or New York.

### Beyond a faster commute

You might think that faster travel times would lead to faster commute times, but, surprisingly, that's usually not the case. Instead, when faster travel is possible, most people choose to use it to travel **further per day**, instead of using it to travel for **less time per day**. (See [Rules of thumb: Marchetti](#marchetti).)

In practice, the result of faster travel times is not shorter commute times for everyone, but is instead an increase in daily **kinematic range** for everyone.

### <a name="kinematic_range"></a>Kinematic range

  * **Kinematic range** is a measure of urban mobility. It's the number of destinations you can get to in 30 minutes or less _(or some other set amount of time)_.
  * Different cities have different kinematic ranges
    * In **Haxby, Montana**, there's not any traffic congestion, but there also aren't many places to go. With a car, in 30 minutes you can probably reach a total of about **a half dozen homes**, with perhaps **10,000 square feet of floorspace**.
    * In **San Francisco**, there are lots of places to go, but there's a lot of congestion. In 30 minutes you can reach hundreds of thousands of homes, offices, and stores, with perhaps **500,000,000 square feet of floorspace**.  San Francisco has a kinematic range that's about 50 thousand times larger than Haxby, Montana.


<object width="1200" height="700" data="../svg/graphs/kinematic_range.svg"></object>

 

<!--
### Congestion vs. kinematic range

  * A **congested** city is one where it's hard to get where you want to go, because there's too much traffic.
  * A **sleepy** little town is one where there's no traffic, but there's almost nothing in town to go to.
  * A **kinematic** city is one that has lots of destinations **_and_** they're all easy to get to.
-->

### <a name="why-does-it-matter"></a>Why does kinematic range matter?

Good mobility is more important than it sounds. It's not just about making rush-hour traffic a little less tiresome. Beyond just convenience, better mobility and kinematic range bring serious changes to the entire metabolism of a city, and to the amount of **opportunity** and **prosperity** available to people.

**For people**, having more destinations within reach means:
  * more **job offers** that are close enough to commute to &mdash; people are statistically more likely to work if they live closer to jobs, and they also have faster job searches and shorter stretches of joblessness[^kneebone]
  * more **friends** & **family** who are actually close enough to drop by
  * more **schools** to choose from, and more **special classes**
  * more **doctors** to choose from, and a wider variety of **specialists** available
  * a wider variety of **churches** and **religious communities**
  * a wider variety of **events**, **meetups**, and **clubs**, and more people who share your interests
  * a wider variety of **[long tail](#glossary:long-tail)** destinations

**For shops**, **employers**, and **industry**, more kinematic range means:
  * more **job candidates** to choose from
  * more **vendors** and **parts suppliers** to choose from
  * more **contractors** in different **specialized fields**
  * more **"[industrial agglomeration](#glossary:industrial-agglomeration)"**, which leads to **"[agglomeration economies](#glossary:agglomeration-economies)"** (somewhat similar to the separate idea of "economies of scale")

**For 911 calls** & first responders, more kinematic range means:
  * **faster response times** and **better incident outcomes**


### <a name="windfall"></a>Kinematic windfall

Around the world, larger cities, with their larger kinematic ranges, tend to have higher wages than smaller cities.

As city size increases, when the number of people (and destinations) in the city grows by 100% (meaning a doubling in size), then the economy of the city tends to grow by about 115% (meaning it more than doubles in size), so that there is effectively a 15% "bonus" in per capita economic output for everyone in the city.[^scale]

This superlinear growth seems to apply to the whole physical and social metabolism of the city, rather than just the economic aspects of the city. The windfall shows up in statistics about:
  * **wages**
  * **wealth**
  * **patents**
  * **AIDS cases**
  * **crime**
  * **restaurants**
  * **diversity of business services** available (meaning, how long the "[long tail](#glossary:long-tail)" of the city is)


<object width="1200" height="700" data="../svg/graphs/superlinear.svg"></object>


  > "The study finds that when inventors move from a smaller to a large cluster, 
  > they experience increases in both the number of patents they generate and 
  > the impact of those patents, based on their subsequent citations. For example, 
  > a computer scientist who moves from the median cluster to a cluster at the 
  > 75th percentile in size would experience a 12 percent increase in productivity, 
  > while an inventor in biology and chemistry doing the same would see an 8.4 
  > percent productivity gain. Overall, a just a 10 percent increase in the size 
  > of a cluster leads to a 0.66 percent increase in the number of patents produced 
  > by a top inventor each year."[^florida]



  > "Third, the clustering of high-tech inventors brings real benefits to the American 
  > economy as a whole. ... [Enrico Moretti] estimates that the U.S. would produce 
  > about 11 percent fewer patents each year under such a scenario. The country would 
  > see a roughly 15 percent annual decline in semiconductor patents, a 13 percent 
  > decline in computer science, and a 10 percent decline in biology and chemistry, 
  > if the geography of inventors was more equal."[^florida]



### <a name="density"></a>Density & kinematic range

In low-density cities, there are fewer destinations within a given distance, so you have to travel farther to have the same kinematic range as you would in a high-density city. In theory, the low-density city could be less congested, so traffic might flow more smoothly, allowing faster speeds and longer distances in a given amount of time. In some cases it does work out that way, but there's a lot of variation, and low-density cities may or may not have good kinematic ranges. 

Low density cities are susceptible to unfortunate feedback loops. Lower density means more suburban sprawl and longer travel distances, which means more total miles of car trips per day, which means that as the city density decreases, the total number of miles of road (and square footage of road) actually increases. If destinations are no longer close enough to have shared parking, then each destination needs it own parking lot, which takes up more space, which in turn leads to more pressure for even lower density further from the city center, which in turn creates more circulation overhead, more miles of road, and so on.

Cities with high population density may or may not have better kinematic range than cities with lower population densities. If you're in a city with a high population, that means there are lots of people within a short distance of you, and lots of destinations within a short distance. But kinematic range is about time, not distance. Some very dense cities suffer from serious congestion, resulting in poor kinematic ranges.



### <a name="existing-cities"></a>The kinematics of existing cities

Larger cities have more total destinations than smaller cities, but some destinations may be too far away for some people to get too. Denser cities have more destinations that are within a shorter distance, but in a congested city, even nearby destinations may take a long time to get to. In practice, different cities have very different kinematics.

Singapore and Dallas-Fort Worth have very different transportation networks, with very different kinematic ranges.

  |---
  | Singapore |  | Dallas-Fort Worth
  |:-:|:-:|:-:
  | roughly 6 million | **population** | roughly 6 million
  | 20,000<br>per square mile | **density** | 600<br>per square mile
  | public transit | **main mode of<br>transportation** | cars
  | 60 minutes | **time it takes<br>for two people<br>on opposite ends<br>to meet in the middle**[^velotopia] | 30 minutes 









### <a name="improvements"></a>Improving existing cities

Existing cities, all over the world, have serious traffic congestion problems[^turbot]<sup>,</sup>[^bliss], despite spending billions on transit projects and on widening roads, in efforts to incrementally improve mobility and kinematic range. As cities grow and economies grow, the congestion problems just get worse.

Cities can improve kinematic range by **moving more people** or **moving people faster**
  * **public transit projects**
    * the **2nd Avenue Subway** project in New York
    * the **Transbay Transit Center** in San Francisco
  * **more highways**, or **more lanes**
    * the **Big Dig** in Boston
  * **more throughput per lane**
    * the **HOV carpool lanes** in Los Angeles
    * the **congestion pricing** in London

Cities can also improve kinematic range by **becoming denser**, so that more people and more destinations are nearby
  * **transit-oriented development**
  * **dense urban cores**
  * **infill development**
  * **multi-use zoning**

Someday, in the future, cities might also be able to improve kinematic range by using **newly invented transit options**
  * **hyperloop** transit tubes
  * **Boring company tunnels**
  * **flying cars**



### <a name="colocation"></a>Co-location in not the answer

"Co-location" is one tempting approach for trying to improve urban traffic congestion problems. Co-location is the idea arranging places in the city so that people are naturally close to where they want to be, to make it so that they don't have to go as far to get to the places they want to go. 

A real-world example of co-location would be a university or boarding school, where dorms, classrooms, cafeterias, and health-care services have all been place on a single campus, so that students can do most of the things they need to do without ever needing to leave campus.

In a city with mixed-use zoning, new developments could include a mix of housing, retail, offices, and light industrial space. People, could, in theory, live right next to where they work.

This idea comes up surprisingly often in essays about new urbanism. Unfortuntely, co-location doesn't isn't actually practical in big cities. It would be practical, if each person only wanted to be connected to one "thing". If all you want is to be at university, then living at the university is practical. Or, if all you want to do in life is go to your job, then living near your office is practical. But in reality, most people are a lot more multi-faceted: they don't just have a job, they also have outside interests like book clubs & sports teams, and they have people in their life that they want to live with or see often, including parents, children, spouses, partners & friends. Most of these people are connected to other places: their own offices, schools, churches, etc. And each of these people has their own set of connected people, branching into a giant social network. Without severing these connections, there is no practical way to "sort" all the people into geographic regions, so that each person is always living near the places they want to get to.

Co-location in not the answer. Co-location is no substitute for mobility.




### <a name="transit_vs_cars"></a>Transit vs. cars

Here in the United States, in discussions about urban planning and transportation, many people fall into one of two opposing camps:

  * **pro-transit people**, who want to see
    * fewer cars on the road
    * less space set aside for parking
    * more bike lanes and bus lanes
    * more funding for some combination of subways, light rail, buses, bus rapid transit, and other public transit
  * **pro-status-quo "car" people**, who 
    * do not want to lose automobile lanes in return for bike lanes and bus lanes
    * do now want to pay the huge costs of creating and operating public transit systems
    * do not want to take slow, inconvenient, public transit options when they could just drive

In addition to the **pro-transit** camp and the **pro-status-quo** camp, there's also a third camp: people who are optimistic about new technologies for **automated, on-demand transportation**, like self-driving cars and delivery drones. 

**Proponents** of shared, self-driving cars point to advantages like the greatly reduced need for parking compared to conventional cars, yet the convenience of direct door-to-door routes.

**Opponents** of self-driving cars point to inherently low throughput-per-lane numbers for cars vs. buses and trains, and the real-world congestion problems that we're already seeing from on-demand car-share services like Lyft and Uber.


### <a name="impossible"></a>The "Impossible City" design proposal

Given what we know about the cost and throughput of cars, buses, and rail, and given what we know about the emerging new alternatives, what's the best we could possibly do?

If we could plan a whole urban transportation network from scratch, what's the optimal mix of different transit modes? Which options are the most affordable, and which ones maximize personal mobility, speedy deliveries, and kinematic range?

What follows is a design proposal for what I believe is a **simple**, **cheap**, **reliable**, **low-risk** transportation network that has **high throughput**, good **transit speed**, nearly **door-to-door** convenience, and takes up less space than roads, leaving more **land area** for parks and buildings.

The **Impossible City** is just one simple design for a more kinematic city. I'm not suggesting that this is the best design; rather, I'm putting it out as a *straw-man* proposal, in hopes that it might be a step in the right direction, and that it might spark conversation that leads to better ideas.

The Impossible design calls for:

  * bikes & **bike-sized vehicles** only, instead of cars, trucks, buses, or trains
  * **electric vehicles** only, instead of gas engines
  * **grade-separated intersections** only, instead of traffic lights, stop signs, or roundabouts
  * **sheltered roads**, sheltered from wind and rain
  * **underground wiring**, instead of telephone poles and overhead power lines

### <a name="look_like"></a>What would it look like?

**A grid**
  * The Impossible design has a **grid of city blocks**, similar to places like Manhattan New York. That's in contrast to older cities like Rome and Paris, which have more intricate street layouts, and in contrast to many 20th century suburban developments or new cities like Dubai, which often have more circular or curvy streets, or layouts that are intentionally asymmetrical, with cul-de-sacs and loops.
 
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

The Impossible design is built entirely around **bicycles**, **bike-sized electric vehicles**, and **sheltered streets** with **no intersections**. At first blush, it's hard to imagine that this is a practical design. It doesn't seem like an entire city could have no buses, trains, or cars, and still manage to move millions of people a day with reduced travel times and increased travel ranges.

It **seems** impossible, because cars **seem** like fast, long-range vehicles, and buses and trains **seem** like high-capacity transit. 

Cars **truly are** fast when they're on highways, but in cities cars are hugely inefficient and ineffective, requiring huge amounts of lane space per car, and traveling with high burst speeds but poor average speeds.

Buses and trains **truly are** high-capacity and high-throughput when everyone on them is going from point A to point B. If you have a group of 50 people who are all gathered together (e.g., at a hotel) and who all need to go to the exact same place (e.g., an office or work site) at the same time, then a bus is a wonderfully efficient and effective choice. But in a city, if people are starting from a variety of different places (different apartment buildings on different blocks), and going to a variety of different places (schools, stores, offices), then buses turn out to have quite poor average throughput.



























<div class="hr"><a name="3"></a></div>

## <span class="chapter">_Chapter 3_ &mdash; Bonus features beyond mobility</span>

If you're building from scratch, then with a few good design choices it's possible to build an urban layout that **works far better** than traditional cities do. New designs can maximize:

  <span class="minor">(A)</span> **[Affordability](#affordability)**

  <span class="minor">(B)</span> ~~Blank (this space intentionally left blank)~~

  <span class="minor">(C)</span> **[Conviviality & convenience](#convenience)**

  <span class="minor">(D)</span> **[Durability, reliability & resilience](#durability)**
 
  <span class="minor">(E)</span> **[Economic prosperity](#economic-prosperity)**

  <span class="minor">(F)</span> **[Freedom, independence & agency](#freedom)**

  <span class="minor">(G)</span> **[Green sustainability](#sustainability)**

  <span class="minor">(H)</span> **[Health & safety](#health)**



### <a name="Affordability"></a>Affordability

There's no point in designing a new urban development that is too expensive to build, and no point in building a new urban development that is too expensive for people to afford to move to.

* **Affordable to build**
  - The Impossible street design uses conventional construction techniques and avoids the most expensive transportation options: 
    * no buses (at $500,000 each, or $8,000+ per passenger seat)
    * no subway cars (at $10,000+ per passenger seat)
    * no subway tunnels (at $100,000,000+ per mile)
    * no automobiles (at $20,000+ each)
    * no multi-story parking garage structures (at $20,000 per parking space)[^carl_walker]
    * no sprawling suburban road network
  - The design lends itself to mid-rise density neighborhoods. Mid-rise housing, for example in buildings with "4-over-1" podium construction, is less expensive to build than skyscrapers, and less expensive than even ten-story buildings with concrete service cores. Mid-rise construction also has lower initial embodied energy per square foot, and lower ongoing operating costs. Mid-rise housing is also less expensive than detached single family housing. [^roaf]<sup>,</sup>[^hoyt]
  - The Impossible street design also offers an optional extra feature that could replace ordinary sidewalks with inclined ramps, which would offer additional cost savings by conserving usable floorspace square-footage (vs. circulation overhead) while entirely obviating the need for elevators, escalators, and stairs. 
  - For new developments built on greenfield sites, land should cost less than what it would cost in an established city. For new developments that are large, the development may gain economies of scale in land acquisition, regulatory approval for planning and permitting, financing, and construction costs & timelines.

* **Affordable to operate**
  - The Impossible street design avoids all the costs of running public transit systems (bus driver salaries, rail car maintenance, etc.) and avoids the costs of private car ownership (insurance, car payments, fuel, new tires, etc.).

* **Affordable to live in**
  - Ideally, the lower costs to build and operate the city will mean that it is more affordable to live in.
    * With lower government transportation subsidies, there is an opportunity to have lower taxes & lower vehicle registration fees.
    * With lower housing construction costs, new housing doesn't need to be as expensive.
    * With a higher-capacity transporation system in place, the Impossible design can support more units of housing before congestion sets in, creating the opportunity for denser zoning and land use plans, more housing construction, and less of the exclusionary zoning supply-side shortages that lead to high housing costs in places like the San Francisco Bay Area.
    * With more units of housing within kinematic range of any given workplace, renters have more choices, landlords face more market competition, and there should be more market efficiency, without artificially inflated prices. Hopefully this will result in market-rate housing that is naturally affordable, without the government having to impose rent control or subsidize affordable housing. Hopefully this might lead to less homelessness, which in turn could lead to lower government spending.
    


### <a name="convenience"></a>Conviviality & convenience

Significantly increased mobility & kinematic range means that it's easier to go see people and easier to get to more places. A more mobile city is a city with more social opportunities and social prosperity.

* **Convivial**
  - easy to go see your friends & family
  - easy to do an errand for your mom
  - easy to go to weird new clubs and meetup groups to see who's there
  - easy for kids to go to parks & playgrounds on their own, without needing a ride

* **Convenient** &mdash; easy access to:
  - school & work
  - groceries & restaurants
  - gyms & laundromats
  - dentists & doctors
  - libraries & museums
  - [long tail](#glossary:long-tail) destinations &mdash; including _That One Unusual Thing_ that most people wouldn't care about, but that you really want to go to:
    * a monthly Renaissance Faire meetup
    * a weekly Burning Man art car workshop
    * a maker space with an Atomic Force Microscope
    * etc.

### <a name="durability"></a>Durability, reliability & resilience

By striving for simplicity, these new designs avoid using lots of "fragile" technologies, like elevators and traffic lights. 

* **Durable** & **reliable** 
  - The Impossible design is a more reliable design, because it has fewer parts that can break, and fewer parts that need power sources. It has a transportation system that can be run by human power alone, if necessary. That's one of the advantages of getting rid of all the traffic lights, buses, subway cars, automobiles, taxis, elevators, escalators, delivery drones, etc.

  > "even when a [New York City subway] station has an elevator, workers have struggled to keep them working properly. Only about 94 percent of elevators were available in August, according to the transit agency. The rate is worse for escalators -- 87 percent were working." [^fitzsimmons]


* **Resilient** 
  - The new design is intended to be much more resilient after a natural disaster like an earthquake, hurricane, or flood. It should be possible to evacuate a building quickly in an emergency, even when the power is out. It should be possible to evacuate a city quickly without running into problems with downed power lines and traffic lights that have gone dark.




### <a name="economic-prosperity"></a>Economic prosperity

A city should provide for a good life for the people who live in it and work in it. As described in [chapter 2](#2), the Impossible design strives to maximize mobility and kinematic range, with the goal of harvesting a superlinear windfall in wages, wealth, patents, land value, etc. The design is intended to create cities that **thrive economically** compared to similarly-sized typical cities, with more prosperity, and greener prosperity.

* **Prosperous**
  - When I say "prosperous", I don't mean Wall Street bankers with vacation homes in the Hamptons. I mean prosperity in the sense of kids who get to go to good schools, teachers who have the books they need, parks with playgrounds and basketball courts, libraries with books & wifi, parents with jobs and health insurance, and jobs with safety standards and protective equipment. These are things that are common in places like rich European countries, and that can become more and more common everywhere in the world. 

* **Green growth**
  - Global poverty is a serious problem, and economic growth is a force for good, so long as the economic growth is "green growth" and so long as GDP growth goes up while carbon footprint goes down, habitat restoration use goes up, and Gini coefficients go down.

> Prud'homme and Lee's paper, titled "Size, Sprawl, Speed and the Efficiency of Cities," shows that productivity per worker is closely correlated to the average number of jobs per worker that are reachable in less than 60 minutes. In Korean cities, a 10 percent increase in the number of jobs accessible per worker corresponds to a 2.4 percent increase in workers' productivity.[^bertaud]


> People who live closer to jobs are more likely to work. They also
> face shorter job searches and spells of joblessness.
> Proximity to employment proves particularly important to certain kinds 
> of workers and residents. For instance, the duration of joblessness among black, 
> female, and older workers tends to be more sensitive to job accessibility than 
> it is for other kinds of workers. For poor residents, living closer to
> jobs increases the likelihood of working and leaving welfare.
> Proximity matters for lower-income, lower-skill workers in particular because 
> they tend to be more constrained by the cost of housing and commuting. 
> They are more likely to face spatial barriers to employment, thus their job 
> search areas tend to be smaller and commute distances shorter.10 In contrast, 
> higher-income, higher-skill workers, who can afford to commute by car and 
> exercise more choice in where they work and live, have more prospects than 
> just the jobs near their neighborhoods and commute longer distances on average.[^kneebone]


### <a name="freedom"></a>Freedom, independence & agency

A city design should not inadvertently restrict people's freedoms, limit people's independence, or obstruct fair access. The Impossible design offers more:

* **Freedom, independence & agency**
  - freedom of movement for everyone in the community 
  
  - freedom to travel without being asked for a license & registration

  - more **kid-friendly** streets
    - kids can visit friends or meet up to play at the park without being dependent on a parent for a ride
    - kids can walk to school without learning how get across dangerous intersections
    - kids can run errands around town for their folks
  
  - more **elder-friendly** streets
    - older people can get out of the house and run errands independently, without needing services like Lyft, Uber, or Meals on Wheels
  
  - more **disability-friendly** space
    - safer streets for people with limited vision or limited hearing
    - better accessibility for people in wheelchairs

* **Fairness**
  - a **level playing field** for urban mobility
  - equal access to safe passage for everyone through all public space
  - full mobility for women[^gadepalli], with no "pink tax"[^mccasland] & no "trip-range" tax[^gonzalez]

* **Accessibility**
  - stroller-friendly buildings and stroller-friendly transportation
  - wheelchair accessible routes to every part of every building
  - predictable navigation for people with limited vision
  - frequent pathside seating for elderly people

    > In 1896, Susan B. Anthony said bicycling was doing "more to emancipate women than anything else in the world." [^kamiya]

    > "Nearly half of American kids walked or biked to school in 1950; today that figure is 13 percent." [^grabar]



### <a name="sustainability"></a>Green sustainability

Compared to a conventional city, the Impossible design should provide:

* **Lower carbon footprint** per capita
  - lower-energy commutes in smaller, more efficient vehicles
  - more efficient heating and cooling of buildings

* **More trees**
  - more trees nearby at any one time, and more trees encountered per day

* **Better air quality**
  - no diesel engines, no gas engines, less motor oil, less tire wear
  - more parks and trees

* **Less noise**
  * no cars and no car noise, means, in practice, less overall noise, even with much higher urban densities [^kang]


### <a name="health"></a>Health & safety

An Impossible City should be **safer** and more fun to live in.

* **Healthier**
  - more opportunity to exercise while commuting
  - better air quality & less noise
  - less stressful, with less traffic congestion and more parks & trees [^macdonald]

* **Safer**
  - no traffic accident deaths
  - faster 911 response time
  - freedom from harassment on buses & subways

    > "over 1.35 million [traffic] deaths and up to 50 million injuries occur every year, with 90% of these fatalities occurring in low- and middle-income countries" [^road-safety]

    > below 18 mph "pedestrians are more likely to survive being hit by a car than die, while at higher speeds the reverse is true" [^levinson]

    > "Small changes in speed have big impacts on fatality rates: a person is 70 percent more likely to be killed by a car moving at 30 mph versus 25 mph." [^ng]

    > "Improvements in response time and medicine are responsible for about one-third of the reduction in fatality rates from crashes in the UK."[^levinson]







### <a name="comparison"></a>How would it compare?

|---
|  | Proposed Impossible City | San Francisco | New York |
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
| **Noise levels** | slightly lower than<br>San Francisco[^kang] | slightly more than<br>proposed city 
| **ADA accessibility**<br>percent of total city floor space | 90% | ?
| **Free-range kids** | yes | no		
| **Power-outage impact**<br>on transit times | no bikeway lights<br>(just daylight/moonlight) | no BART<br>no traffic lights
| **Daylighting**<br>Spatial Daylight Autonomy (sDA) percent<br>Annual Sun Exposure (ASE) percent<br>(also several others)
| **Home sizes**<br>square feet per person, average | 275 | 275 |
| **Office space**<br>square feet per person, average | 260 | 260 |
| **911 response time**<br>minutes, average | 4 minutes | 5.75 minutes |	
|---



















<div class="hr"><a name="4"></a></div>

## <span class="chapter">_Chapter 4_ &mdash; Why this matters now</span>

Figuring out how to design better cities is especially important right now, at this moment in history, for a few reasons.

* **[The urban population boom](#population-boom)**
  - Urban population is about to increase by 60%, with **2.5 billion more people** incoming by 2050.
* **[The urban construction boom](#construction-boom)** 
  - There is projected to be a **doubling of total built space** by 2050.
* **[The rise of "megacity" urban agglomerations](#megacities)**
  - By 2050, we will have 175 cities with populations between 4 million and 40 million.
* **[The onset of kinematic lag](#kinematic-lag)**
  - Large cities are increasingly suffering from congestion and kinematic lag.
* **[The mounting lost opportunities](#lost-opportunities)**
  - Kinematic lag is already a problem that artificially depresses global GDP by trillions of dollars per year, slowing the rise out of poverty of billions of people.
* **[The rising current opportunities](#current-opportunities)**
  - If we could get better at city design now, then in the next few decades **we could prevent additional losses** from kinematic lag on the order of **$5 trillion dollars per year**, as well as seeing a windfall of **$15 trillion** in residential real estate value. Unfortunately, in practice, that will be impossible.

There's no way to cheaply or practically re-build existing cities, or move people _en masse_ from existing cities to new cities, but, when new cities, new suburbs, and new satellite developments are being planned and built from scratch, it would be slightly crazy to fail to try designing them as "kinematic cities". Building from scratch has its own challenges, and is also crazy expensive, but it does have the advantage that it can be done much more quickly. 

The Impossible design does not depend on a particular climate, or on particular building materials. It's an anywhere-in-the world city, not just a European city, an African city, or an Arctic city. It could be built on the outskirts of an existing city, or it could be built in a brand new "greenfield" site.

> "If you build a new city you don't have to relocate or work 
> around existing roads or rivers or factories or houses. 
> You also don’t have to work around existing political processes, 
> community groups, civic organizations ... or even existing 
> regulations and rules."[^growth]
> &mdash; John Macomber, senior lecturer, Harvard Business School.



### <a name="population-boom"></a>Urban population boom

In the next 30 years, **by 2050**, urban population is expected to grow by 60%, with another **2.5 billion more people** living in cities.[^growth]

  |---
  | Year | Urban<br>portion<br>of world | Total urban population[^un-desa] |
  |-:|:-:|:-
  | 1950 |     | 0.75 billion
  | 2018 | 55% | 4.2 billion
  | 2050 | 68% | 6.7 billion
  |---

Perhaps existing cities will absorb nearly all of the 2.5 billion additional people who will live in cities by 2050, but in doing so some of their suburbs will essentially develop into big satellite cities of their own right. The Impossible City ideas are relevant for how new developments in those satellite cities are designed. If 4% of those 2.5 billion additional people did move to entirely new urban developments, that would be 100 million people in new urban developments. 

### <a name="construction-boom"></a>Urban construction boom

Existing cities are **too few and too small**, by a factor of two, for everyone who will live in them by 2050. To handle the influx, cities will build another **2.5 trillion square feet** of new buildings. These numbers can be hard to believe at first. For different projects by different authors, see the [notes about urban growth](#growth) below.

This wave of construction is going to happen no matter what, whether we prepare for it or not. People will build housing for themselves, even if they can't do it legally, in slums and informal settlements like those in Kibera, Dharavi, Neza, and Orangi Town. If we could muster more planning, forethought, and funding, then these new developments could end up with infrastructure like comprehensive sewer systems and high kinematic-range transportation networks. 

> "If we stick to business as usual most of it is going to be 
> disorderly and less functional than the stuff we already have."[^growth]
> &mdash; Paul Romer, Nobel prize-winning economist, New York University.



### <a name="megacities"></a>"Megacity" urban agglomerations

Currently, the world has about 33 "megacities", where a megacity is defined as an urban agglomerations with more than 10 million inhabitants. The world is projected to have 43 megacities by 2030, and about **50 megacities by 2050**, with an additional 125 large-but-not-mega cities that land in the range between 4 million and 10 million inhabitants.[^ontariotech]

  > City clusters already exist of course, like the Randstad in the Netherlands, which links Amsterdam, Rotterdam, The Hague, and Utrecht. The urban development around San Francisco Bay could also be considered a city cluster. What is different with the Chinese concept of cluster is their scale. The Randstad connects only 7 million people, while San Francisco Bay (including Silicon Valley) has only 6.2 million people. By contrast, the urban cluster of the Pearl River Delta already had 65 million people in 2010, larger than the entire population of the United Kingdom but concentrated on less than 10,000 square kilometers! The recent urban cluster including Beijing-Tianjin-Hebei links together more than 105 million people.[^bertaud]


### <a name="kinematic-lag"></a>Kinematic lag

[Kinematic range](#kinematic-range) generally increases as cities get bigger. I believe that increase in kinematic range is what drives the [superlinear scaling](#superlinear) effect.

As a city grows, at first, kinematic range increases as population increases, perhaps in a roughly linear relationship. Unfortunately, as cities get too big, they start to sprawl and suffer from traffic congestion. Eventually, there's a **kinematic lag**, where the kinematic range stops its 1-to-1 tracking of population growth, and begins to lag behind.

This whole Impossible Cities proposal is all about trying to reduce that kinematic lag in larger cities. The proposed Impossible City design is an attempt to keep increasing a city's kinematic range even as its population grows in the multi-millions. 

As the world adds more and more large cities and megacities, kinematic lag becomes a bigger and bigger problem, kinematic range becomes more important, and design ideas like the Impossible City design become more important.

<object width="1200" height="700" data="../svg/graphs/kinematic_lag.svg"></object>

> "Contrary to common perception, megacities have not been driving global
> growth for the past 15 years. In fact, many have not grown faster than their host
> economies, and we expect this trend to continue. We estimate that today's 23
> megacities will contribute just over 10 percent of global growth to 2025, below
> their 14 percent share of global GDP today. Instead, we see the 577 fast-growing 
> middleweights ... contributing half of global growth to 2025, gaining share from 
> today's megacities. Worldwide, we will see 13 middleweight cities become 
> megacities by 2025."[^mgi]


 
### <a name="lost-opportunities"></a>Lost opportunities

Take the **San Francisco Bay Area** as an example. The Bay Area is a conurbation that encompasses major cities like San Francisco and San Jose, as well as lots of smaller cities, like Oakland, Berkeley, and Mountain View. The entire population is about 8 million people, depending where you draw the boundaries. 

If you estimate floorspace at about 600 square feet per person, that means there's about 5 billion square feet of floorspace in the Bay Area. Your thirty-minute kinematic range [(**KR<sub>30</sub>**)](#glossary:KR30) would be **5 billion square feet**, if you could magically get from any point in the area to any other point in under 30 minutes. But you can't.

As a rough estimate, let's say that from any room in any random building in the Bay Area, within 30 minutes you can reach about one quarter of the other buildings in the Bay Area. That means your actual 30-minute range would be about **1.25 billion square feet**.

If we could just improve your travel times enough, we could quadruple your KR<sub>30</sub> range. If kinematic range is in fact what drives the [superlinear scaling](#superlinear) effect, then doubling the 30-minute range for the Bay Area would yield a 15% windfall in average hourly wages, patents per capita, GDP, etc. Doubling the 30-minute range gets you a 15% windfall, and quadrupling gets you **a 30% windfall** (actually more like 32%, because 1.15<sup>^2</sup> is 1.3225).

**GDP.** The San Francisco Bay Area GDP was about $535 billion in 2019.[^facc]  A 30% annual increase would be an **additional $160 billion annual GDP**.

**Real estate.** The San Francisco Bay Area has about $1.3 trillion of residential real estate. A 30% increase in value would be a $400 billion increase, just for the residential portion of the real estate. Commercial real estate would be roughly another $400 billion. There would also be additional floor space in the roadway buildings, which might amount to another $200 billion, for a total of about $1 trillion of additional real estate value. San Francisco is one of just a few cities in the United States that has a market value higher than the $1 trillion Apple Inc. value.[^hoeven] But other cities have even higher real estate values. In New York City, the housing alone is worth $1.5 trillion. In the Upper East Side, housing value has reached $100 billion per square mile.[^metrocosm]

**Hope?** I’m not suggesting that anyone could somehow re-build the San Francisco Bay Area to quadruple kinematic range, but I am saying that hypothetically, if the Bay Area had been built kinematically to begin with, then the real estate would be worth $1 trillion more than it is now. In the case of the Bay Area, that's $1 trillion in real estate value that somehow got left on the table: value that was lost just because of past choices about streets, geometry, and buildings. 

Is it conceivable that the Bay Area could be re-engineered to quadruple travel ranges? Yes, but it would require a lot of changes: maybe a hyperloop, or a lot of Boring Company tunnels. It would be expensive, and it would take decades. The Bay Area has already calcified, and for all practical purposes, big changes now are pipe dreams. For context, here are a few examples of the giant cost of modest mobility improvements:
  * the 2013 Bay Bridge Eastern Span, from San Francisco to Oakland, took over a decade to build and cost $7 billion
  * the 1976 BART system was a comparable amount, if measured in today's dollars
  * the 2006 Big Dig in Boston cost $21 billion


### <a name="current-opportunities"></a>Current opportunities, GNP

As of 2017, the worldwide gross national product (GNP) was about $80 trillion per year. Some of that GNP comes from rural activities, like farming, and other remote activities, like mining and fishing. But the majority of GNP, more than 80%, comes from urban areas, for a total of about $65 trillion per year.[^mgi]<sup>,</sup>[^khan]

By 2050, global GNP will probably roughly double, to about $160 trillion per year. By 2050, more than $140 trillion of that total is likely come from the urban areas. 

Some of those "urban areas" are actually small towns with just a few thousand people, but increasingly, the majority of the urban population will be living in larger and larger cities, and those large cities also generate a disproportionately high amount of the total GNP. By 2050, about 16% of the world's population, 1.6 billion of the world's 9.8 billion people, will be living in the world's 175 largest cities, with 4 million to 40 million people each.[^ontariotech] A conservative estimate suggests those 175 cities will contribute $30 or $40 trillion per year to worldwide GNP.

Because of their size, all of those 175 cities will probably suffer from kinematic lag. If we could intervene, and by 2050 we could somehow double the kinematic range in each of those cities, we could expect to yield a 15% kinematic windfall on the GNP from those cities. A back-of-the-envelope calculation suggests that would be an ongoing windfall of maybe **$4 trillion to $6 trillion per year** in increased GNP. Other authors give significantly higher values for annual return in increased GDP from urbanization:

> In Africa "we should be building 40 million new homes or 160 Atlantas every year. ... 
> Africa has 54 countries. Altogether they do not build 1 million homes a year. 
> The gap is the opportunity. 40 million modest homes require an investment of 
> more than $1 trillion every year. The multiplier effects would add $10 trillion 
> to annual GDP. That is 5 times current GDP. Closing Africa's housing gap can 
> generate 5 times current GDP!"
> &mdash; Paul Musembwa, CEO of Warp Developments

> In a paper published in 2015, the economists Chang-Tai Hsieh and Enrico Moretti 
> found that, between 1964 and 2009, the high cost of housing in some US cities 
> relative to wages had lowered aggregate US GDP by 13.5 percent: "Most of the 
> loss was likely caused by increased constraints to housing supply in high 
> productivity cities like New York, San Francisco and San Jose. Lowering 
> regulatory constraints in these cities to the level of the median city would 
> expand their work force and increase U.S. GDP by 9.5%.[^bertaud]



### <a name="current-opportunities"></a>Current opportunities, land value

In the San Francisco Bay Area, the total residential and commercial real estate is worth about $2.6 trillion. 

The total value of all real estate, worldwide, was about $280 trillion at the end of 2017. Of that total, most is residential real estate, at $220 trillion, with just $33 trillion of commercial real estate and $27 trillion of agricultural real estate. Worldwide, residential real estate is worth more than all of the equities & debt securities combined. [^savills]

In Manhattan, land value grew at an annual rate of 5.5 percent beyond inflation 1950 to 2015.[^manhattan] That's an unusually good return, but in general real estate value has increased at roughly the same pace as GNP. By 2050, total worldwide real estate might be worth about $560 trillion.

By 2050, the world's 175 largest cities will have residential real estate worth more than $100 trillion. If we could double the kinematic range in those cities, we could expect to yield a 15% kinematic windfall, for maybe a **$15 trillion** increase in residential real estate value. Unfortunately, trying to double the kinematic range of even a single city is probably impossible.

In a world where another 2.5 billion people will be moving into cities in the next 30 years, we should think twice about how much prosperity we want to leave on the table. Real estate developers who care about the value of their land should care about building kinematically. And it's not just real estate. It's also hourly wages, GDP per capita, and patents per capita. Our current cities are sub-optimal to the extent that there are hundred of billions of dollars of lost value per major city. Anyone, or any coalition, who can optimize on that can begin to harvest that windfall. In practice, the windfall would get split up between lots of different parties, with enough incentives to go around.

There would be:

  + **company founders**, with early equity stakes in the companies involved
  + **inventors**, getting royalties on patents for, say, new spatial layouts
  + **architects** getting licensing fees on blueprints & construction specs
  + **property managers**, getting lease and rent income
  + previous **land-owners**, profiting on the sale of land to the new city
  + **real estate developers**, getting property value appreciation
  + **anchor employers**, getting tax incentives & incentive investments
  + **new employees**, getting big relocation bonuses & brand new housing
  + **early homeowners**, getting in the ground floor on property values
  + **county governments**, getting new property tax revenue
  + **state governments**, getting new income tax revenue
  + **local airports**, getting new flights & additional passenger revenue
  + etc.
















<div class="hr"><a name="5"></a></div>

## <span class="chapter">_Chapter 5_ &mdash; Why this is impossible</span>

We know that:
* The world is rapidly building more cities & bigger cities. (See <a href="#4">chapter 4</a>)
* For new urban areas, we could design new 21st century transportation networks that would work far better for people than the default 20th century designs. (See chapters <a href="#1">1</a>, <a href="#2">2</a> & <a href="#3">3</a>)

Unfortunately, actually building cities this way is probably impossible, because of:
* **<a href="#location">Location problems</a>**
* **<a href="#network-effect">Network effect problems</a>**
* **<a href="#cost">Cost problems</a>**
* **<a href="#bootstrapping">Bootstrapping problems</a>**
* **<a href="#land-value-capture-problems">Land value capture problems</a>**



### <a name="location"></a>Location problems

These new urban development designs could be built in a few different types of locations, but they all have problems:

* **Infill in existing cities** and/or rebuilding portions of cities
  - Retrofitting infrastructure in existing cities can be several times more expensive than building new infrastructure in new sites.[^haas]
  - Land is much more expensive to acquire in existing cities than in remote areas.
  - Opportunities for buying large parcels of land are rare.
  - There are no easy ways to integrate the new Impossible neighborhood's transportation network into the existing city's transportation network(s). (See [network effect problems](#network-effect) below.)
  - Neighbors frequently oppose developments that increase density.
  - Zoning restrictions typically restrict changes in land use and density.
    - For example, 75% of residential land in Los Angeles is restricted to single-family homes, as is 94% of land in San Jose[^buhayar]
* **New suburbs** and/or satellite cities around existing cities
  - Land anywhere **near** large cities is expensive
  - Large parcels are rare.
  - Connections between the new suburb's Impossible-style transportation network and the city's existing transportation network(s) will require people to transfer between vehicles mid-trip, and will decrease mobility and kinematic range. (See [network effect problems](#network-effect) below.)
* **[Greenfield cities](#glossary:greenfield-city)** and/or "new city" developments
  - Before starting construction, the new city project will need to pre-purchase (or otherwise reserve) all of the adjacent land that the city may someday need to grow into. Starting with anything less than 100 square miles of land may mean the new development is restricted from ever growing to become a "megacity" urban agglomeration, in which case it will fail to realize its kinematic windfall potential.
  - Starting from scratch, a new greenfield city will start off with almost no population initially. Even if there were immediate and uninterrupted exponential population growth from then on, it will still take decades for the new city to become a "megacity", by which time the window of opportunity will have already passed, with the mid-century urban population surge and urban construction surge having already reached their peaks.
  - Good greenfield sites are hard to find. A good site should have:
    - enough land
    - proximity to existing cities that are thriving
    - proximity to ports and airports

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



### <a name="network-effect"></a>Network effect problems

Depending where construction happens, the Impossible Cities design faces one of two different network effect problems.

* **Population growth network effects** &mdash; for new greenfield city sites
  * People move to cities because of the opportunities there, or because they know people there. The bigger the city, the more draw it has. Once a major city has become established, and has a critical mass, it's not difficult to find people who want to move there. Kids are born and raised in existing cities, not in greenfield city sites. If a new town is founded from scratch, with a small population, in a remote place, then it probably doesn't have enough critical mass to draw people to come live there. It's a chicken-and-egg problem: in order to attract a lot of people, a city has to be big, but before it can become big, it has to have attracted a lot of people.
  * A small-scale Impossible City would work just fine, and it would have some advantages over a similarly sized car-centric or transit-centric city. Lower transportation costs might be the largest single selling point. But the advantages may not be large enough to matter to anyone. For small-scale cities, car-centric designs actually work reasonably well, as do designs based on buses and bus rapid transit. The car & bus system only starts to break down once a city gets large enough to have serious traffic congestion problems, and it's only at that scale that the Impossible City design starts to really outshine the other options.

* **Transportation system network effects** &mdash; for infill and suburb/satellite sites
  * Different transportation systems tend not to be complementary. 
  * Dallas-Fort Worth is a car-based city. Cars work fairly well there, allowing millions of people to reach each other in under 30 minutes. Dallas-Fort Worth does also have a light rail system, DART, but it has less than 100,000 daily riders, because it only has 4 lines, with 64 stations, which means it doesn't effectively connect any two points in the city. The network of car-based streets **does** connect any two points in the city. Free parking is available at more than half of the DART stations, but if you already have a car, and you're already in your car, it may be faster and more convenient to just drive to your final destination, rather than drive to the DART station, park, wait for a train, pay a fare, ride the train, and then walk from the station to your destination.
  * New York City, by contrast, has a subway system with 5 million daily riders, using 36 lines with 470 stations. In New York, the subway system works well because it has achieved critical mass, effectively connecting most points in the city. Cars also work in New York, but street congestion makes cars slow, and parking is a problem. In general, the car network & the subway network tend to be alternatives to each other, rather than being a unified system. The subway stations generally don't have parking lots or taxi stands, and a trip will take longer if it involves both a car leg and a subway leg.
  * An Impossible City design could be used to build a small-scale neighborhood in, or near, an existing car-centric city, either in an infill site or as a new suburb or satellite city. The problem with that scenario is that it may be the worst of both worlds: outside of the new neighborhood you have to use a car to get around, but within the new neighborhood there are no roads and no parking, so you can't use a car. The Impossible bikeways would work well for trips **within** the new neighborhood, but not for any trips across town, crossing back and forth **between** the new neighborhood and the rest of the city. For trips across town, you still need a car and you still fight urban traffic congestion, but then you can't drive right up to your office, and instead have to park somewhere at the edge of the kinematic neighborhood and then switch to foot or small vehicle to get the last distance. That means the trips would take *longer* because people would have to have both a car leg and a bikeway leg, with the need for parking and a transfer in between. In this situation, in terms of mobility and kinematic range, people would actually have been better off if the new neighborhood had been built to match the transportation system of the rest of the city, rather than introducing a new design.
  * A more natural pairing would be small-scale Impossible neighborhoods centered on train stations for either subway trains, or light rail, or commuter trains like the San Francisco Bay Area Caltrain. That's a workable design, but there may not be much opportunity for it in existing cities. In existing cities, the area around subway stops and train stations is typically already very developed, with expensive real estate, and expensive existing buildings, and lots of land reserved for streets, so that the remaining parcels are separated into islands. It would take a lot of time and money to try to rebuild a few square miles of that into a kinematic neighborhood.

### <a name="cost"></a>Cost problems

Constructing even small buildings is expensive. Constructing entire neighborhoods or entire cities requires not just building housing and office space, but also building all the transportation infrastructure for roads, street lights, traffic lights, bus shelters, subway stops, and more. Plus all of the utility infrastructure, including sewers, water supply, power lines, telephone lines, and the rest.

* **Low cost** vs. **high cost** locations
  * An Impossible City could be built in a high-cost location, such as California, or in a lower-cost location in a higher-growth area in India or Africa, like somewhere near the new Bagamoyo port and special economic zone, near Dar es Salaam, Tanzania. Starting in a lower-cost location is almost certainly a more promising approach, but it means that the benefits will be correspondingly lower. A 15% kinematic increase in wages & GDP is less dramatic if the wages & GDP were low to begin with, even if higher population growth and GDP per capita growth is expected.
  * In a place like San Francisco or New York, average construction costs are about $350 per square foot. That means, for example, that new apartments can cost over $400,000 per unit to build.[^li]<sup>,</sup>[^reid]
  * Even in the lowest-income countries, where construction labor is least expensive, the basic costs of steel and concrete amount to about $50 per square foot. That means even a very small single-room apartment can cost $5,000 to $10,000 in construction materials alone.[^bertaud]
  
    > "As of 2018, land prices near downtown Washington, D.C. and San Francisco were well over $10 million per acre, compared to around $100,000 per acre in Cleveland and Detroit." [^hoyt]
    
* **Coordinated funding** vs. **parallel funding**
  * Real estate development projects have traditionally happened on the scale of one building at a time, or one small housing complex or office park at a time. A booming city may have hundreds or thousands of building projects going on in parallel, each with their own different land owner, general contractor, bank loan, and prospective tenant, and each with their own zoning and planning department approval. That arrangement lowers the bar for any single project, and enables lots of projects to move forward simultaneously, each at their own pace, without needing to coordinate tens of billions of dollars of funding and spending. Each project can be tuned to the needs of the particular parties involved, resulting a vibrant diversity of approaches and results, rather than the less successful giant mono-culture developments sometimes found in planned economies. For an Impossible City project to succeed, it would be necessary to try to let as many small projects as possible play out in parallel, but that requires first establishing a coordinated overall system that establishes a framework for zoning, planning, property ownership, infrastructure development, etc. 
  * In recent decades, the largest development projects in the world have been growing larger. Projects on the scale of $10 to $20 billion are now fairly common. Some of those are transportation infrastructure projects, such as the Chunnel, the Gotthard Base Tunnel, the Riyadh Metro, and the New York 2nd Avenue subway project. Others are more focused on creating large amounts of leasable square footage, such as Masdar City, or the Hudson Yards project in New York. However, when a single project has a $20 billion price tag, funding is still typically coordinated from multiple sources, usually with significant public funding in the mix. Notable exceptions are privately funded projects like the Apple Park campus in Cupertino, at $5 billion, or the City Center project in Las Vegas, at $11 billion, the largest privately funded construction project in the history of the United States.[^wiki_citycenter] Any privately funded new city project would almost certainly need to have initial completion costs of no more than $10 or $20 billion.
* **Upfront costs** vs. **ongoing costs**
  * Getting a new city started would be more feasible if it were possible to minimize the upfront costs, so that substantial costs only start to occur later, once people have already moved in, value is being created, and revenue opportunities are available. Unfortunately, the Impossible City design doesn't lend itself to minimizing upfront costs. Because of the [network effect](#network-effect) problems, there's not much incentive to try starting a small project; a more promising approach would be to try to scale up as quickly as possible, but that would require raising funds from speculative investors, rather than funding growth on revenue from the value created.



### <a name="bootstrapping"></a>Bootstrapping problems

The problem of how to minimize upfront costs comes down to a bootstrapping problem, and amounts to a chicken-and-egg problem. A new city project doesn't actually have to build a huge new city over night, but how do they create a minimum viable seed that's large enough to spin up enough economic activity to propagate its own growth?

At a minimum, it seems like the project founders would need to:
  * buy a huge amount of land on day one 
  * zone it all so that it can grow in a kinematic shape (without getting clogged up with junk like traffic lights and parking garages) 
  * find "anchor employers" to build majors project there, such as a port, a corporate headquarters, or a government capital



Building even a small seed of an Impossible City would take a long time and lot of resources. A minimum viable start might need:

  + a city charter (the legal documents)
  + an independent city government
  + one or more corporate real estate development partners
  + tens of square miles of fairly empty land
    - it needs to be fairly empty, yet not remote
    - it needs to be clear of conservation restrictions and legal show-stoppers
  + existing local construction companies
  + wholehearted support from existing county & state governments
  + wholehearted support among the neighbors
  + big "anchor employers" (like Amazon, or the Indonesian Government)
  + a pent-up demand of people eager to move into new housing as it is completed
  + a pent-up demand of companies eager to move into new office space as it is completed
  + an existing airport, port, and interstate highway not too far away
  + start-up capital:
    - billions of dollars (in Africa)
    - or tens of billions (in the US)
    - existing construction firms & hundreds of experienced construction teams
    - reliable supplies for millions of pounds of steel, concrete, and prefabricated parts
  + a few years of time, for initial construction work, to build:
    - enough housing and office space for tens of thousand of people
    - covered laneways for vehicle circulation
    - a power grid
    - water supply
    - a sanitation system
    - other minimum basic infrastructure



### <a name="land-value-capture-problems"></a>Land value capture problems

Building good urban infrastructure, including transportation infrastructure, is extremely expensive. But in a city with good transportation infrastructure, the value created by the transportation infrastructure far exceeds the cost of the infrastructure. 

* **Value created**
  * Real estate values are higher in parts of the city that are closer to transit stations, and when new transit stations open the real estate values nearby rise. 
  * For example, when the new 2nd Avenue subway line in New York was built, property values along the subway corridor rose by 10% relative to the rest of the Upper East Side. It is estimated that total value of all that residential and commercial real estate rose by an additional $7 billion as a result of the subway line being built.[^jaffe]
  * When the San Francisco Bay Area BART system built their Fremont extension, home values near the new station outpaced home values further away by a margin of about 9% to 15%, which amounted to an additional windfall of about $100,000 to $200,000 per home for all the homes within 2 miles of the new station, for an aggregate value of about $1.7 billion.
  * This is true not just for transit stations, but for any sort of access to transportation. For example, in Manhattan, corner lots are significantly more valuable than mid-block lots, and lots close proximity to Broadway also have higher values.[^manhattan]

    > "Based on the studies in Asian countries including China, Singapore and South Korea, 
    > public transportation generally has a positive impact on property values, and the 
    > impact is closely related with distance to the station. On average, property value 
    > will decrease by 1% if the distance from a transport station is increased by 10% 
    > (Cervero & Murakami, 2009)."[^xu]

    > "In most studies, proximity to transport stations has a positive correlation to land value. 
    > They can generate property value premiums ranging from 3% to 40% in different conditions 
  > (Medda, 2012)."[^xu]


* **Privatized gains and socialized costs**
  * Unfortunately, the cost of the transportation infrastructure development is generally paid by governments, using public funds, while the value create is harvested by private property owners. This is similar to the problem of "privatized gains and socialized losses". As a result, governments generally can't afford to invest as much in transportation infrastructure as it would make sense to. Because of the disconnect between the investment costs and the return on investment, cities end up under-investing in mobility and kinematic range.
  * The solution to this underinvestment problem is to structure the financial system to better connect the investment costs with the return on investment. This is not a new idea. For example, the **Georgism** movement dates back to the 1870s, when Henry George wrote his best-selling _Progress and Poverty_. One of the central ideas of Georgism is to tax land value, rather than tax labor.


* **Land value capture**
  * With "value capture" or "land value capture", the idea is to somehow set things up to recoup a big portion of the actual observed gain in land value that's created by a given investment in transportation.[^xu]<sup>,</sup>[^jaffe] Different cities around the world have tried different approaches to land value capture, including:
    - simple property taxes or land value taxes (which may fail to capture much of the value created)
    - tax increment financing (TIF), in places like New York
    - leasing development rights to land, in places like Hong Kong


* **Effective capture**
  * Some land value capture approaches are **much** less effective than others. The most effective approaches all have a few things in common:
    - they tend to rely on good coordination of land use, city planning and economic development [^xu]
    - they don't work as well in developed areas, and work better in undeveloped areas that have more room to grow [^jaffe]
    - they work in situations where the transportation developer can purchase land at a reasonable price[^xu]


* **Catch-22**
  * That crux of the problem is that the place we really need better mobility is in 
existing big cities, but those are the places where all the land is already privately owned, it's difficult to do much land value capture, and so it's hard fund transportation infrastructure improvements. To add insult to injury, these existing big cities are also the places where transportation projects are the most expensive to do, working in tight spaces on complicated projects, with high labor costs and high real estate costs.


* **Hong Kong**
  * Hong Kong stands out as a great example of successful land value capture and successful urban transportation investment. Hong Kong is a rare example of a city where public transport actually runs at a profit. [^xu]
  * Hong Kong is unusual, in that all land in the Hong Kong Special Administrative Region is state property (with the exception of St. John's Cathedral), and has been since 1843. The land is available for use only through leasehold, not private ownership. The government is responsible for land management, development, and the leases to private parties. Private developers bid on an open market to lease parcels of land, typically with 50 years lease terms. [^xu]
  * The government-owned Mass Transit Railway (MTR) Corporation acts as the master planner. It manages the whole real estate development cycle, all the way from drawing up plans, monitoring work quality, and managing the lease of completed projects.
  
    > "One reason that projects like Tsing Yi Station come into success is that the land use integration is evaluated at the master planning stage by MTR."[^xu]

    > "Hong Kong's strategy can be applied in cities where government owns the land."[^xu]

* **Depreciating licenses**
  * Hong Kong serves as an outstanding real world example, and in theory it should be possible to craft even more successful mechanisms for land value capture and urban transportation investment. There are many of avenues worth exploring here, and that's beyond the scope of this paper. But, just as a single example, one promising idea for land value capture is the use of **depreciating licenses**, which can help to improve allocative efficiency. [^weyl]

> "With the right framework, astonishing prosperity is possible. The independent city of Singapore overtook the world’s GDP per capita in less than 30 years, and that of the USA in less than 50 years." [^free-private-cities]





### <a name="summary"></a>Possible vs. Impossible

|---
| | Possible | Impossible | 
|:-:|:-:|:-:
| **Vehicles needed**<br>(existing) | <object width="30" data="../svg/logos/checkmark.svg"></object> | 
| **Construction technology**<br>(existing) | <object width="30" data="../svg/logos/checkmark.svg"></object> | 
| **[Location problems](#location)**  | | <object width="30" height="40" data="../favicon.svg"></object> 
| **[Network effect problems](#network-effect)**  | | <object width="30" height="40" data="../favicon.svg"></object> 
| **[Cost problems](#cost)**  | | <object width="30" height="40" data="../favicon.svg"></object> 
| **[Bootstrapping problems](#bootstrapping)**  | | <object width="30" height="40" data="../favicon.svg"></object> 
| **[Land value capture problems](#land-value-capture-problems)**  | | <object width="30" height="40" data="../favicon.svg"></object> 
|---



















<div class="hr"><a name="faq-etc"></a></div>

## <span class="chapter">_FAQ, etc._</span>

* **[FAQ](#faq)**
* **[Rules of thumb](#rules-of-thumb)**
* **[Effective altruism](#effective-altruism)**










<div class="hr"><a name="1"></a></div>

## <a name="faq"></a><span class="chapter">FAQ: Frequently Asked Questions</span>

### <a name="could-we-build"></a>Could we build an Impossible City?

**Yes.** The Impossible City plans are designed with existing technology in mind, and with an eye toward simple, affordable technologies. It's about bicycles and water pipes, not about floating ocean domes and orbital towers.

### <a name="could-we-transform"></a>Could we turn London or Paris into an Impossible City?

**No.** Existing cities have a lot of physical infrastructure that's expensive to change. People can make incremental changes, like adding new roads or bridges, but it's not practical to change the fundamental layout and transportation network of an existing city.

### <a name="could-ideas-trickle-down"></a>Could Impossible City ideas trickle down to existing cities? 

**Yes.** Over time people in existing cities like New York and San Francisco could adopt some of the ideas in the Impossible City designs, and make their cities incrementally more kinematic, even if they can't change the fundamental layouts. One "simple" change would be re-stripe some of the lanes on some of the roads so as to split an existing automobile lane (at, say, 12 feet wide), into two side-by-side bicycle-sized vehicle lanes (at, say 6 feet wide each).

### <a name="do-ideas-impact-democracy"></a>Do Impossible City ideas impact democracy and governance?

**No.** The Impossible City designs are politically neutral. The designs are only about transportation systems and about the physical, spatial layout of the buildings in the city.

An Impossible City could have a traditional city government structure, or it could experiment with less conventional structures. That's a big topic, and one for another author. Suffice it to say, the questions of governance are largely orthogonal to the ideas presented here about the physical layout of a city, the transportation choices, etc. An authoritarian government could build an Impossible City, or a utopian libertarian collective could build an Impossible City, and they would both be Impossible Cities.















<div class="hr"><a name="1"></a></div>

## <a name="rules-of-thumb"></a><span class="chapter">Rules of thumb</span>

  * <a name="marchetti"></a>**People tend to travel about one hour a day.**
    * For people who commute, the average commute is about 30 minutes each way.
    * For people who aren’t commuting, it is common to spend about an hour each day on other sorts of trips: chores, errands, appointments, etc.
    * This "one hour per day" number has been found to be surprisingly consistent across different cities in different centuries, different cultures, and different continents, regardless of the different modes of travel used to commute. This is called the **Marchetti constant** (named for Cesare Marchetti, although it was really Yacov Zahavi who first wrote about it).

  * **As supply increases, consumption goes up.**
    * The <a name="jevons"></a>**Jevons paradox**, or Jevons effect, says that if it becomes possible to use a resource more and more efficiently, then instead of using less of the resource, people actually use more. Total consumption increases because demand increases as efficiency drives the costs down.
    * <a name="induced-demand"></a>**Induced demand** says that as the supply of a resource increases, more of it will be consumed. If you add a new lane to a congested highway, it does not result in reduced congestion and faster trips, but instead results in an increase in the total number of trips made. Induced demand might be better described as **latent demand**. The demand was actually there all along, there was just a lack of supply to meet the demand. The concept of induced demand is often used as an argument against increasing roadway traffic capacity. I think this is misguided. The existence of latent demand is a sign that we should be striving to increase the supply of transportation capacity, and increase [Kinematic Range](#kinematic-range).[^wiki_induced_demand]


  * **Some aspects of a city scale linearly.**
    * If a city doubles in population size, many measurable characteristics of the city, such as the number of businesses, also double in size. Around the world, from small towns to big cities, regardless of the size of city, there's always about one business establishment per 22 people, and an average of about 8 employees for each establishment.[^scale] 

  * **Some aspects of a city scale sub-linearly.**
    * There are often economies of scale in the infrastructure of big cities (or at least, economies of density). 
    * If a city doubles in population size, meaning it grows by 100%, parts of the supporting infrastructure tend to only grow by 85%. This is tends to be true for networks of roads, electrical cables, and municipal sewers and water pipes.

  * **Some aspects of a city scale super-linearly.**
    * <a name="superlinear"></a>**Superlinear scaling** is the phenomenon where if a city population grows by 100% (meaning it doubles in population size), then the economy of the city tends to grow by about 115% (meaning it **more than doubles** in size), so that there is effectively a 15% "bonus" in per capita economic output for everyone in the city.[^scale] This 15% superlinear growth seems to apply to the whole physical and social metabolism of the city, rather than just the economic aspects of the city. The 15% surplus shows up in statistics about:
      * wages
      * wealth
      * patents
      * AIDS cases
      * crime
      * restaurants
      * variety of business services available (meaning, how long the "long tail" of the city is)

    > "... it's illuminating to ask how many different types of businesses there are in a city. ...
    > The data confirm that diversity systematically increases with population size. ... 
    > an extrapolation of the data strongly suggests that if we could measure diversity to 
    > the finest possible resolution it would scale logarithmically with city size."[^scale] &mdash; Geoffrey West

  |---
  | City Population | Average Hourly Wage<br>(this is not actual observed data,<br>just example numbers) | Superlinear Scale Factor |
  |-:|:-:|:-:
  | 40,000 | $16 | (-15%)^4 below $28
  | 80,000 | $18 | (-15%)^3 below $28
  | 160,000 | $21 | (-15%)^2 below $28
  | 320,000 | $24 | -15% below $28
  | 640,000 | **$28** | **100% average**
  | 1.25 million | $32 | +15% above $28
  | 2.5 million | $37 | (+15%)^2 above $28
  | 5 million | $43 | (+15%)^3 above $28
  | 10 million | $49 | (+15%)^4 above $28
  |---


> Economic literature linking the wealth of cities to spatial concentrations is quite abundant and is no longer controversial in academic circles. ... The 2009 World Bank Development Report "Reshaping Economic Geography," and the report of the Commission on Growth and Development "Urbanization and Growth" (published the same year) exhaustively summarize and document the theoretical and empirical arguments justifying the economic advantage provided by the spatial concentration of economic activities in large cities.[^bertaud]
> &mdash; Alain Bertaud


> "High-tech invention is extraordinarily concentrated in just a handful of cities. ... The top 10 city-regions account for nearly 60 percent of inventors in biology, chemistry and medicine, with greater New York and the San Francisco Bay Area accounting for more than 10 percent each. Seventy percent of inventors in computer science are in the top 10 regions; the Bay Area alone has more than one-quarter of them. And the top 10 regions account for almost 80 percent of inventors in semiconductors, with one-quarter again in the Bay Area and another 15 percent in greater New York." ... "This clustering of inventors has only increased over time, growing by about five percentage points for biology, chemistry, and medicine, 15 percentage points for computer science, and about 20 percentage points for semiconductors between 1971 and 2007."[^florida]



  
* <a name="sublinear"></a>**Sublinear growth (economies of scale)** is the phenomenon where if a city population grows by 100% (meaning it doubles in population size), then the network of roads, electrical cables, and other supporting infrastructure of the city tends to grow by about 85% (meaning it **less than doubles** in size), so that there is effectively a 15% "bonus" economy of scale, both economically and environmentally.[^scale] 

  > "Once one starts to think about (the causes of economic growth),
  > it is hard to think about anything else."
  > &mdash; Robert Lucas, Nobel laureate in Economics 




































<div class="hr"><a name="effective-altruism"></a></div>

## <span class="chapter">Effective altruism</span>

Effective altruism is the idea of trying to find the most cost-effective interventions for improving global well-being, and then directing money and resources towards those efforts. Non-profit research organizations like GiveWell<sup>([link](https://www.givewell.org/))</sup> work hard to evaluate wide arrays of possible interventions and try to find the most effective ones. Private foundations like the Gates Foundation have similar internal research departments.

The idea of building Impossible Cities might be worth studying as a candidate intervention for effective altruism. Building cities is far more expensive than most philanthropic interventions, but it also has the potential for a variety of simultaneous large-scale positive outcomes.

* **Basic housing**
  + Housing is a basic human need. Non-profits like Habitat for Humanity focus on housing construction. Other non-profits run homeless shelters, promote "Housing First" housing, provide affordable housing & emergency housing, set up refugee camps, etc. An Impossible City built on the outskirts of Dar es Salaam, for example, would be in the midst of a population where one-third of the people are malnourished and two-thirds of are living below a poverty level of $1.25 per day. An Impossible City project like this could serve as a large-scale intervention to provide basic housing to a population in need, while also providing a large amount of market-rate housing. 

* **Sewer & water systems**
  + More than half the world's population lacks adequate access to clean water, toilets, and good sanitation systems. Inadequate sanitation is estimated to kill hundreds of thousands of people per year. Organizations like the Gates Foundation are working hard on providing sanitation, and they report that every dollar spent on sanitation is estimated to provide at least five dollars in economic return. For a new Impossible City built for underserved populations, the city's sewer and sanitation system alone would be a significant philanthropic intervention.

* **Poverty intervention**
  + If the Impossible City design does prove to help reduce kinematic lag, and if a new Impossible City is seeded in a location where it will grow large, then the kinematics of the design itself should serve as a powerful anti-poverty intervention. The Impossible City construction should be slightly less expensive than traditional urban housing & transportation systems, so the kinematic benefits come essentially "for free", simply as a result of the geometry of the streets and buildings.

* **Climate change intervention**
  + The Impossible City design offers a low-carbon approach to large-scale 21st century development. Building even a single, small-scale Impossible neighborhood could serve as a proof-of-concept and study model for further developments. Early funding for an initial prototype development might have a disproportionately high impact, in the same way that successful research & development efforts can sometimes have high impact per dollar invested.
  
* **Disaster relief**
  + The Impossible City design lends itself to being built quickly, because of the simplicity of the design. If necessary, an Impossible City could be completely built and fully functional even without any traffic lights, elevators, buses, HVAC systems, windows, or central power grid. Better still would be to already have some excess capacity of half-built cities on hand before disaster strikes.
  + In the decades to come large-scale disasters will come more frequently, as cities get bigger, weather events get more severe, and sea levels rise. The disasters will increasingly require large-scale refugee housing on short notice.  In addition to natural earthquakes and tsunamis, there will be an increasing number of climate-related disasters:
    - wildfires, like the 2018 California fires and the 2019-2020 Australian Black Summer bushfires
    - flooding events, like the 2013 and 2016 Indian floods
    - levee failures, like the 2005 New Orleans flood wall failures
    - typhoons, like China's 1975 Typhoon Nina
    - mud-slides, like Venezuela's 1999 Vargas mud-slide
    - heat waves, like the 2003 and 2006 European heat waves

* **Education**
  + There are significant urban-vs-rural disparities in the quality of education that kids receive. Non-profits and governments try to address that problem as best they can, by, for example, incentivising teachers to move to rural villages. But that only goes so far. Rural kids will still, on average, be further away from a school, have fewer school & class choices, and have less exposure to large pool of educated, literate adults working in a variety of professions (for example: doctors, nurses, clergy, mechanics, and engineers).
  + By making urban housing more affordable, the Impossible City design would help enable more people to move from rural to urban settings, and result in more kids having the advantages and opportunities of an urban environment.

* **Women's rights**
  + There are also significant urban-vs-rural disparities in women's rights. The UN reports that, with few exceptions, rural women fare worse than urban women for each of the Millennium Development Goal (MDG) indicators. Women and girls in urban settings have more access to education, health care, and family planning services, and more access to jobs and support services.
  + The Impossible City design goes a step further than conventional cities, by decreasing barriers to mobility. There's no silver bullet for preventing sexual assault and harassment, but the Impossible City design can enable people, including women & girls, to travel through a significantly larger chunk of city without having to wait at night at bus stops, walk through subway tunnels, or ride in taxis or Uber cars. The Impossible City design helps provide equal access to mobility and kinematic range, which in turn helps provide equal access to all the opportunities that fall within that kinematic range.
  
* **Family planning intervention**
  + There are significant urban-vs-rural disparities in women's ability to choose how many children to have. Across a range of countries, rural fertility levels are significantly higher than urban levels. Part of the urban-rural fertility gap can be attributed to demographic differences in things like income levels and education levels. But even after adjusting for demographic differences, a significant portion of the fertility gap appears to be attributable to the setting itself, urban vs. rural. Rural fertility is almost 20 percent higher than urban fertility, for matched cohorts.[^lerch]
  + An Impossible City project would add to the supply of urban space, help meet unmet demand for urban housing, and by accelerating the ongoing urban-rural demographic transition, would help provide more individual choice in family planning decisions while also helping to reduce the population pressure that we collectively are putting on the planet, as the global human population swells from the current 7.8 billion up to something like 9.7 or 9.8 billion by 2050.












<div class="hr"><a name="appendixes"></a></div>

## <span class="chapter">_Appendixes_</span>

* **[Books and software](#further-reading)**
* **[Glossary](#glossary)**
* **[Hypothetical locations](#hypothetical-locations)**
* **[Impossible City design summary](#design-summary)**
* **[Source material](#source-material)**
* **[References](#references)**













<div class="hr"><a name="1"></a></div>

## <a name="further-reading"></a><span class="chapter">Books & software</span>

### Books

* _[Carfree Cities](http://www.carfree.com/book/)_, by J.H. Crawford

* _[Order without Design](https://mitpress.mit.edu/books/order-without-design): How Markets Shape Cities_, by Alain Bertaud

* _[Scale](https://www.penguinrandomhouse.com/books/314049/scale-by-geoffrey-west/)_, by Geoffrey West

* _[Soft City](https://islandpress.org/books/soft-city)_, by David Sim

* _[Velotopia](https://www.nai010.com/en/publicaties/velotopia/130528)_, by Steven Fleming

* _[Urban Bikeway Design Guide](https://nacto.org/publication/urban-bikeway-design-guide/)_, and the [other street design guides](https://nacto.org/publications/design-guides/), by the The National Association of City Transportation Officials (NACTO)

### Software Tools

* [Brookings: metropolitan area "nearby jobs" maps](https://c24215cec6c97b637db6-9c0895f07c3474f6636f95b6bf3db172.ssl.cf1.rackcdn.com/framed/2015/jobproximity-110.html): An interactive web page with maps showing heat-maps of the number of nearby jobs in different United States metropolitan areas. See also: ["The growing distance between people and jobs in metropolitan America"](https://www.brookings.edu/research/the-growing-distance-between-people-and-jobs-in-metropolitan-america/).

* [OnTheMap](https://onthemap.ces.census.gov/): An interactive web page with maps showing information about workplaces, jobs, and commute distances for any the United States city, county, census track, or user-defined area.

* [Sidewalk Widths NCY](https://www.sidewalkwidths.nyc/): An interactive web page with a map showing the width of the sidewalk of each city block in New York.

* [Streetmix](https://streetmix.net/): An interactive web page where you can design and redesign different street layouts, making different choices for street & lane widths, lane-use types, sidewalks, parking, etc.

* [SUMO](http://sumo.sourceforge.net/): Simulation of Urban MObility. An open source traffic simulation package designed to handle large road networks.

* [TravelTime platform](https://www.traveltimeplatform.com/blog/commute-time-visualization-map), by iGeolise, Ltd










<div class="hr"><a name="1"></a></div>

## <a name="glossary"></a><span class="chapter">Glossary</span>

* **agglomeration economies<a name="glossary:agglomeration-economies"></a>**
  * The idea of agglomeration economies is similar to the separate idea of "economies of scale". Agglomeration economies are the economic benefits that come from "industrial agglomeration", which means the clustering of a lot of business firms in one region. (Our designs to be mindful of avoiding "agglomeration diseconomies", which are the disadvantages of proximity, such as traffic congestion.)

* **architectural, engineering and construction (AEC)<a name="glossary:AEC"></a>**
  * the entire industry of companies and people who build structures
  
* **build-operate-transfer (BOT) agreement<a name="glossary:BOT"></a>**
  * an agreement where a private company or consortium builds and operates some new project or facility (such as an airport or a sewer system) for a set amount of time (such as 30 years), after which ownership of the whole facility is transferred back to the government

* **building information modeling (BIM)<a name="glossary:BIM"></a>**
  * instead of old 2D paper blueprints for architectural designs, BIM uses digital models of buildings, where the models include not only the 3D geometry of the building, but also information about specific part numbers for components, costs, sustainability analysis information, etc.
  
* **charter city<a name="glossary:charter-city"></a>**
  * a special jurisdiction with a blank slate in commercial law, to allow for the adoption of new practices in areas such as a business registration, labor law, tax administration, and commercial dispute resolution
  * _typically built on greenfield sites to avoid the challenges of implementing such a wide array of reforms in an existing polity_
  * _typically privately financed_
  * see: [special economic zone](#glossary:SEZ)

* **co-design<a name="glossary:co-design"></a>**
  * an design approach where stakeholders and end users are partners in the design process 

* **community land trust (CLT)<a name="glossary:CLT"></a>**
  * A nonprofit organization that owns land and sells or rents housing units (or retail or office space) built on the land, usually with the goal of providing affordable housing. A household typically leases a unit for a 99-year term, rather than buying a house outright, or may buy a house outright but leases the land that the house built on. Members elect a board so that the CLT is democratically self-governing. When a member sells a unit, the CLT may collect a cut of the sales price (in practice, as high as 75%), which it can use to subside purchases for new homeowners. [^schneider_2019-04-29]

* **curb-cut effect<a name="glossary:curb-cut-effect"></a>**
  * systems designed to benefit vulnerable groups, such as the disabled, often end up benefiting all of society
  
* **effective altruism<a name="glossary:effective-altruism"></a>**
  * using empirical analysis to direct resources towards efforts that do the most possible good
  * _anti-malaria efforts, deworming initiatives, and direct cash transfer programs are among the interventions most widely credited with providing the most cost-effective improvement in welfare for the global poor than any other intervention_ 
  * see [GiveWell](https://www.givewell.org/)

* **generative design<a name="glossary:generative-design"></a>**
  * a design process in which a computer generates a large number of possible solutions, and iterates towards more optimal designs, based on sets of constraints and design evaluation criteria

* **global compact on refugees (GCR)<a name="glossary:GCR"></a>**
  * a 2018 United Nations draft agreement on refugees

* **global compact on safe, orderly and regular migration (GCM)<a name="glossary:GCM"></a>**
  * a 2018 United Nations agreement about international migration [^wiki_gcm]

* **greenfield city<a name="glossary:greenfield-city"></a>**
  * a greenfield project is a project that starts from scratch and is unconstrainted by having to fit within a framework established by prior work, and a greenfield city is a city development project built on a greenfield site of previously undeveloped land

* **Harberger tax<a name="glossary:harberger-tax"></a>**
  * a property tax system in which a property owner declares a self-assessed value for their own property, pays tax as a percentage of that value, and agrees to immediately sell the property to any buyer who offers the self-assessed value 

* **High Line<a name="glossary:high-line"></a>**
  * an greenway park in New York City, built as a rails-to-trails conversion of a section of elevated railway, inspired by the Promenade plantée in Paris

* **housing cooperative** or **housing co-op<a name="glossary:housing-co-op"></a>**
  * A group of households in a multi-family building, where each household owns a share of the whole building co-op and has the right to occupy a single unit, rather than owning that unit outright. An elected board makes decisions. [^schneider_2019-04-29]

* **inclusionary zoning<a name="glossary:inclusionary-zoning"></a>**
  * city zoning restrictions that requires (or incentivizes) private developers to private some portion of the units in a new building at a below market rate

* **induced demand<a name="glossary:induced-demand"></a>**
  * if you add lanes to a freeway, it leads to more trips, not faster trips [^wiki_induced_demand]

* **industrial agglomeration<a name="glossary:industrial-agglomeration"></a>**
  * see [agglomeration economies](#glossary:agglomeration-economies)

* **isochrone map<a name="glossary:isochrone-map"></a>**
  * a map with concentric isochrone lines around a center location, where all the points on any given line represent places that are equally distant, in terms of travel time, from the center location [^wiki_isochrone]

* **Jevons paradox<a name="glossary:jevons-paradox"></a>**
  * as **X** gets faster (and cheaper), people use more **X** [^wiki_jevons]

* **kinematic<a name="glossary:kinematic"></a>**
  * concerned with the motion of bodies, and their range of motion

* **kinematic range (KR)<a name="glossary:kinematic-range"></a>**
  * as a measure of urban mobility, the number of destinations (jobs, schools, friends) that you can get to in a given amount of time

* **kinematic range<sub>30-minute</sub> (KR<sub>30</sub>)<a name="glossary:KR30"></a>**
  * the number of destinations you can get to in 30 minutes of travel time

* **land value capture<a name="glossary:land-value-capture"></a>**
  * any method whereby a city or other community arranges to fund infrasucture development (such as a subway system) by recovering and reinvesting the increases in land value that result from public investment

* **limited equity housing co-op<a name="glossary:limited-equity-housing-co-op"></a>**
  * a type of co-op building, owned collectively by the residents, available only to low-income or moderate-income buyers, at below-market buy-in prices, and with restrictions on resale that limit the profit that members can make when they sell

* **long tail<a name="glossary:long-tail"></a>**
  * On Amazon, some popular books, like Harry Potter books, sell lots of copies. An obscure book may sell almost no copies, but there are **lots** of different obscure books, and togther the obscure titles sell more copies than the popular ones. Some statistical distributions, like the one that describes Amazon book sales, have a "long tail", which means that the uncommon items, when taken together, end up being just as significant as the common items, or more so. If a book seller sold **all** the popular titles but no unpopular ones, they would be failing to meet **most** of the demand for books. Similarly, if the city bus routes go to all of the popular destinations, but nowhere else, then they fail to meet most of the demand for mobility. <span class="minor">(Picture by <a href="http://www.haykranen.nl/">Hay Kranen</a>.)</span>

<figure style="text-align: center; padding-bottom: 1em;">
  <object data="../svg/graphs/long_tail.svg"></object>

  <figcaption class="minor" style="text-align: center">
<= more common &nbsp; &nbsp; vs. &nbsp; &nbsp; less common =>
</figcaption>
</figure>


* **Marchetti constant<a name="glossary:Marchetti-constant"></a>**
  * People will commute about 30 minutes each way per day
  * <a name="marchetti"></a>The **Marchetti constant** says that **people tend to travel about one hour a day**. The Marchetti constant is named for Cesare Marchetti, although **it was really Yacov Zahavi** who first wrote about it.
  * For people that commute to a job, the average commute is about 30 minutes each way. For people who aren't commuting, it is common to spend about an hour each day on other sorts of trips: chores, errands, appointments, etc. 

  > In the United States in 2013, commuting trips represented only 20 percent of weekday urban trips, 28 percent of vehicle kilometers traveled, and 39 percent of public transport passenger-kilometer traveled.[^bertaud]
  
  The one-hour number seems to be surprisingly consistent across different cities in different centuries, different cultures, and different continents, regardless of the different modes of travel used to commute. The one-hour constant is believed to have held true in:
  + Ancient Rome
  + Medieval Paris
  + Victorian London — steam train
  + New York — subway
  + Los Angeles — car 

  > "Using data from cities across several countries, including the United States, England, Germany, and some developing nations, [Yacov] Zahavi discovered the surprising result that the total amount of time an average individual spends on travel each day is approximately the same regardless of the city size or the mode of transportation. ... we tend to spend about an hour each day traveling, whoever and wherever we are. ... the average commute time from home to work is about half an hour each way independent of the city or the means of transportation.
  > 
  > ... the increase in transportation speed resulting from the marvelous innovations of the past couple of hundred years has not been used to reduce commuting time but instead has been used to increase commuting distances. ... the size of cities has to some degree been determined by the efficiency of their transportation systems for delivering people to their workplaces in not much more than half an hour's time."[^scale] &mdash; Geoffrey West

* **metrics<a name="glossary:metrics"></a>** & **measures<a name="glossary:measures"></a>**

  * **floor area<a name="glossary:floor-area"></a>** &mdash; the amount of floorspace in a building, including the floorspace on all the different floors of a multi-story building.
    * **gross floor area<a name="glossary:gross-floor-area"></a>** &mdash; the total [floor area](#glossary:floor-area) of a building, including all the area taken up by lobbies, hallways, elevator shafts, walls, offices, apartments, etc.
    * **usable floor area<a name="glossary:usable-floor-area"></a>** &mdash; the subset of the [gross floor area](#glossary:gross-floor-area) that could be rented out to be used exclusively by a tenant, or sold for the exclusive use of an owner (for example, a studio apartment, or a dentist's office).
    * **occupied floor area<a name="glossary:occupied-floor-area"></a>** &mdash; the subset of the [usable floor area](#glossary:usable-floor-area) that is being used, not sitting vacant. 
    * **circulation area<a name="glossary:circulation-area"></a>** &mdash; for a building, the [floor area](#glossary:floor-area) of a building taken up by hallways, elevator shafts, stairways, and lobbies. (Or, for a city, the additional [land area](#glossary:land-area)  taken up by streets and sidewalks, parking lots, driveways, bus stops, train tracks, etc.)

  * **floor area ratio (FAR)<a name="glossary:FAR"></a>**
    * **FAR<sub>parcel</sub><a name="glossary:FAR-parcel"></a>** &mdash; the [floor area ratio](#glossary:FAR) for a building on a parcel, meaning the ratio of [floor area](#glossary:floor-area) to [parcel area](#glossary:parcel-area).
    * **FAR<sub>overall</sub><a name="glossary:FAR-overall"></a>** &mdash; the [floor area ratio](#glossary:FAR) for a neighborhood of a city, meaning the ratio of the total [floor area](#glossary:floor-area) of all the buildings to the total [land area](#glossary:land-area) of the neighborhood, including all the land area used for streets and sidewalks and parks, as well as the land area of all the [parcel area](#glossary:parcel-area).
    * **circulation area ratio<a name="circulation-area-ratio"></a>** &mdash; the ratio of the total [circulation area](#glossary:circulation-area) of a city to the total [usable floor area](#glossary:usable-floor-area). In New York City, for typical Manhattan city blocks, the streets and sidewalks take up 30% of the land area, with the remaining 70% available for building parcels. Within an office building, hallways, stairs, and elevators typically take up 30% of the [floor area](#glossary:floor-area) of the building, leaving only the remaining 70% as [usable floor area](#glossary:usable-floor-area).

  * **GDP per capita**

  * **kinematic range<sub>t=30_minutes</sub><a name="glossary:KR30"></a>** &mdash; the total amount of [occupied floor area](#glossary:occupied-floor-area) a person could possibly get to in [30 minutes](#marchetti).

  * **kinematic range (KR)<a name="glossary:KR"></a>** &mdash; the total amount of [occupied floor area](#glossary:occupied-floor-area) a person could possibly get to in some fixed amount of time. KR is a measure of **mobility**, and a measure of the capacity and efficiency of a transportation network. The KR measure serves a proxy represents the range of destinations that a person can get to. In the real world, a destination would be something like your friend's house, your dentist's office, or a library or coffee shop.
    * **factors:** kinematic range is a function of lots of different factors:
      * **_starting location_** &mdash; are you starting at the center of town, or out at the edge?
      * **_urban density_** &mdash; how many destinations are there per square mile?
      * **_mode of transport_** &mdash; are you walking, or in a car?
      * **_encumbrances_** &mdash; do you have a stroller, or a wheelchair?
      * **_age_**, **_race_**, & **_gender_** &mdash; can you safely take the subway, or do you need to take a cab?
      * **_time of day_** &mdash; are the trains even running at this hour?
      * **_traffic congestion_**
      * **_travel bans_** & **_security checkpoints_** &mdash; are you allowed into that area?

  * **land area<a name="glossary:land-area"></a>** &mdash; the total size of all the land occupied by a city.

  * **parcel area<a name="glossary:parcel-area"></a>** &mdash; the size of the lot of land that a house (or other building) is built on.

  * **population<a name="glossary:population"></a>** &mdash; the number of people who live in a city

  * **population density<a name="glossary:population-density"></a>** &mdash; the number of people per [land area](#glossary:land-area). Alternatively, you can also think about density in terms of [floor area](#glossary:floor-area) per person.

* **new urban agenda (NUA)<a name="glossary:NUA"></a>**
  * a 2016 United Nations agreement serving as a guideline for global urban development from 2016 to 2036 [^wiki_habitat_iii]

* **refugee city<a name="glossary:refugee-city"></a>**
  * a proposal for a type of [special economic zone](#glossary:SEZ) (SEZ) for displaced people [^castle-miller]
  * see also: [sustainable development zone](#glossary:SDZ) (SDZ)

* **special economic zone (SEZ)<a name="glossary:SEZ"></a>**
  * a part of a country in which the business and trade laws are different from the rest of the country [^wiki_sez]
  * there have been SEZs since the 1950s, and there are now thousands of SEZs around the world [^mason]

* **sustainable development zone (SDZ)<a name="glossary:SDZ"></a>**
  * a proposal for designated areas that are designed to promote economic development via a combination of governance and physical infrastructure, in economies composed of displaced people [^sustainable_development_zones]
  * see also: [refugee city](#glossary:refugee-city)

* **tax increment financing (TIF)<a name="glossary:TIF"></a>**
  * special tax districts around targeted redevelopment areas, where future tax revenues are diverted to finance infrastructure improvements or development [^schneider]

* **transportation poverty<a name="glossary:transportation-poverty"></a>**
  * poor access to transportation, which can result from a variety of contributing factors, such as: areas where most housing is far from a bus or railway line, areas where housing is far from goods and services, and areas where average incomes make it expensive to own and operate a car

* **urban consolidation center (UCC)<a name="glossary:UCC"></a>**
  * neighborhood-level freight hubs, place around the edge of a town, where trucks or large vehicles drop off packages to be loaded into small vehicles, like electric cargo bikes, for last-mile delivery



















<div class="hr"><a name="1"></a></div>

## <a name="hypothetical-locations"></a><span class="chapter">Hypothetical locations</span>

Just as a thought experiment, it can be interesting to look at regions of existing cities and think about which places might be large enough to sustain a new car-free kinematic district...

### Treasure Island, near San Francisco

**Question:** Would a site like Treasure Island (including Yerba Buena Island) be a suitable test site for a new neighborhood with an Impossible City design? It's about 2.5 square kilometers, but currently only has a population of about 2,500?

**Answer:** No, Treasure Island is too small. Also too remote -- being entirely surrounded by water is a loss in terms of commute times and ranges. Ferries are slow. Cars are subject to all the existing traffic congestion. A BART extension would cost billions, and perhaps tens of billions. Potentially that BART extension alone would be more expensive than an entire seed neighborhood on a 50-square mile greenfield site.

Treasure Island would certainly have huge market demand. Every apartment you built would rent for thousands of dollars a month. But buying all the land on Treasure Island, at market prices, would cost you billions. And construction costs would be $500 per square foot, so even once you owned the island, it would still cost $400,000 per apartment to build housing. If you built office space too, and high schools, and police stations, pretty soon you've got a construction budget up over ten billion for this "small scale" starter project!

In contrast, buying 50 square miles in a satellite location on the outskirts of a city in Africa could be relatively affordable, and you might be met with a warmer welcome in the whole multi-year design review & permitting process.

### Brisbane, California

Brisbane Baylands would be a better site than Treasure Island. The city of Brisbane, just south of San Francisco, does have a large undeveloped parcel that would be big enough to build a bit of an Impossible City in.

Brisbane Baylands has slightly more land area than Treasure Island, and there's no new construction work already underway like Treasure Island has. Plus the Caltrain commuter train and highway 101 run right through Brisbane Baylands, and a Muni light rail station is there. It's also immediately adjacent to San Francisco, with no bridge crossing or ferry required.

Brisbane Baylands already has a private land owner and private developer that want to build on it. It could be a great location for a kinematic district, but only if the voters in Brisbane wanted denser development, which they don't.

### Standford University, California

The Standford University campus, at 13 square miles, is more than an order of magnitude larger than Treasure Island and would be a candidate for a new Impossible City district. It's also already situated in a developed urban area, with good connectivity to highways 101 and 280, Caltrain, and two existing international airports. And, unlike Treasure Island, it's not surrounded by water, which means all the area immediately around it falls into its kinematic range.

But for Stanford to work as a location, people would have to be willing to tear down some of what's already built there. And the whole project would only be possible in some very like scenario where the city of Palo Alto were willing welcome hundreds of thousands of new neighbors, with all the strain that would bring on already congested highways, airports, and train lines.

### Other San Francisco Bay Area sites

There are other sites all around the Bay Area that are big enough and well located, if it were possible to get approval to build densely on them. Half Moon Bay, Pescadero, or, oddly, the huge empty space right in middle of the Bay itself, north of the Dumbarton bridge and south of the 92 bridge, which in many ways would be nearly perfect, except for the fact that construction in the Bay is completely off limits, given its status as a protected nature reserve. 

### The Sea Ranch, California

Further afield, there's the Sea Ranch. It has more land area than the Stanford Campus, but with a population of only 1,300 people, so there is only a small pool of existing owners to buy out, and a small number of buildings to be moved, removed, or incorporated into the new plans. The weather is great, the views are great, the hiking is great. But it's remote: it's only got a tiny airport, and no port, no rail, no major highway. I think it would only really work in some science fiction scenario where you could build a hyperloop tunnel to San Francisco and Silicon Valley.

### Northern California Coast

There are other similar sites up the California coast, like in the Eureka area, with similar pros and cons. Or the area around the Little River Airport by Mendocino, if the State of California suddenly decided to allow development in the State Park property.

The Northern California Coast is one of a number of unusual places in the world. For some sorts of development projects, it might prove to be a "Goldilocks" location, with a rare collection of attributes:
* coastal location that could have sea ports
* within a couple hundred miles of the established, thriving, high-GDP urban agglomeration (the San Francisco Bay Area), which has significant unmet demand for housing, office space, and manufacturing space
* low population density, with large, empty counties that average just a few dozen people per square mile across thousands of square miles
* low land prices
* enjoys a moderate, Mediterranean climate (no need for air conditioning, only mild needs for heating, and no need to protect plumbing from winter freezes)
* projected to still have a moderate climate even in 2050 or 2100, after significant global warming makes many other places either too hot, too dry, or too prone to severe storms and flooding
* latitude within 45 degrees of the equator, with adequate sunshine and non-extreme seasonable variation in daylight hours
* stable legal environment with fairly predictable rule of law



### Greenfield locations

Alternatively, instead of looking at locations in places like California, it might be easier, faster, and more fruitful to work with people who are already in the process of planning large new developments on open greenfield sites, the way people are doing in Asia, Africa, and the Middle East.

### Fast-growing locations

The best locations might be ones that are close to the cities that are expected to grow the most dramatically in the coming decades and have very large populations by 2050:

  |---
  | City | 25-year<br>growth<br>projection | 25-year<br>growth % | 2050 population<br>projection [^ontariotech]<sup>,</sup>[^wiki_projections_of_population_growth] | 2025 population<br>projection [^wiki_projections_of_population_growth]
  |:-|:-:|:-:|:-:|:-:
  | Kinshasa, DRC           | 18 million | 109% | 35 million | 17 million
  | Lagos, Nigeria          | 17 million | 107% | 33 million | 16 million
  | Mumbai, India           | 16 million | 61% | 42 million | 26 million
  | Delhi, India            | 14 million | 61% | 36 million | 23 million
  | Dhaka, Bangladesh       | 13 million | 60% | 35 million | 22 million
  | Karachi, Pakistan       | 13 million | 66% | 32 million | 19 million
  | Kolkata (Calcutta), India | 12 million | 61% | 33 million | 21 million
  | Dar es Salaam, Tanzania | 10 million | 181% | 16 million | 6 million
  | Kabul, Afghanistan      | 10 million | 138% | 17 million | 7 million
  | Manila, Philippines     | 9 million | 59% | 24 million | 15 million
  | Cairo, Egypt            | 8 million | 54% | 24 million | 16 million
  | Nairobi, Kenya          | 8 million | 143% | 14 million | 6 million
  | Khartoum, Sudan         | 8 million | 102% | 16 million | 8 million
  | Baghdad, Iraq           | 7 million | 87% | 15 million | 8 million
  | Chennai (Madras), India | 6 million | 61% | 16 million | 10 million
  | Lahore, Pakistan        | 6 million | 53% | 17 million | 11 million
  | Luanda, Angola          | 6 million | 74% | 14 million | 8 million
  | Bangalore, India        | 6 million | 61% | 16 million | 10 million
  | Hyderabad, India        | 6 million | 61% | 15 million | 9 million
  |---










<div class="hr"><a name="1"></a></div>

## <a name="design-summary"></a><span class="chapter">Impossible City design summary</span>

### <a name="transportation"></a>Transportation

The Impossible City design calls for:
  * **no cars** within city limits
    * no private cars
    * no taxis
    * no ubers, lyfts
    * no waymos and self-driving cars
  * **no rail** within city limits
    * no subways
    * no light rail
    * no trollies or trams
  * **nothing airborne** within city limits
    * no delivery drones
    * no helicopters
    * no gondolas
  * **nothing big**
    * no buses or bus rapid transit (BRT)
    * no trucks
    * no mass transit
  * **no gas engines** in vehicles
    * no motorcycles
  * **nothing fast**
    * no motorcycles
  * **no stops** &mdash; keep traffic flowing
    * no traffic lights
    * no stop signs
    * no large intersections
    * no personal rapid transit, pods, people movers, or things with fixed stops
  * **no freeways**, and no free roads

Instead, the design has:
  * <a name="bikeish"></a>**bike-sized vehicles**
    * mixed-use vehicles
      * Some people may own their own bikes, wheelchairs, or other vehicles, which they can park at home or in parking spaces at their destination.
      * Some people may choose not to own their own vehicles, and instead use vehicle rental services such as Mobike, Lime, Motivate, or JUMP Bikes.
      * Some people may choose to travel in pedicabs or other small vehicles that have a human driver or are self-driving.
    * Innovation is NOT REQUIRED
      * An Impossible City could be built today using off-the-shelf bikes and other vehicles purchased from amazon.com.
    * Innovation IS POSSIBLE &mdash; an Impossible City can incorporate new products as they emerge on the market, such as
      * new models of electric bikes, scooters, etc.
      * scooters and bicycles that can autonomously reposition themselves from where they are left to where they are needed. (Companies like Tortoise and Uber are working on autonomous scooters.[^dickey])
      * small vehicles that are fully self-driving, like self-driving wheelchairs, go-karts, or other single-person vehicles
      * wireless charging stations at public parking spaces
      * automated congestion pricing
      * battery swapping services
  * **covered laneways**
    * rain-sheltered pedestrian sidewalks
    * rain-sheltered bike-sized lanes &mdash; 5-foot wide lanes, not 10' or 12' wide car lines
  * **laneway tolls** & **parking tolls**
    * no tolls on laneways that aren't congested
    * highest tolls at rush-hour, or on busy laneways
    * tolls are per-minute, not per-mile (to prevent slow "street blimp" advertising vehicles)
    * free parking when space is ample
    * highest parking tolls in congested areas
  * common-carrier **delivery lockers**[^quirk]
    * package-delivery lockers, located along the laneways
    * shared by Amazon, FedEx, UPS, USPS, and anyone else who would like to use them

### <a name="spatial-layout"></a>Spatial layout proposal

A Impossible City design has:
  * **no highways**
  * **no roads** with lanes wide enough for cars and trucks
  * **no empty rooftops**
  * **no single-story buildings** such as ranch houses &mdash; (don't squander land area)
  * **no skyscrapers** and no high-rise residential buildings &mdash; (keep construction costs down)
  * **no private suburban lawns** 

Instead, it has: 
  * mid-rise buildings of about **six stories, similar to Paris**
  * **row-houses** and "walk-up" apartments
  * buildings spaced to avoid dark areas that would be far from windows and skylights &mdash; (keep lighting costs down)
  * buildings with ventilation chimneys &mdash; (keep HVAC costs down)
  * buildings with windows that open
  * a grid of **bike-sized boulevards**
    * rain-sheltered boulevards, each with four narrow bike-sized lanes, each 5 feet wide, plus shoulders
    * grade-separated intersections, so your entire commute has no stop signs or traffic lights
    * a grid of highline trails above the bike boulevards
  * city blocks of about 660 feet by 660 feet
  * about one iconic **landmark structure** per million people, inspired by examples such as:
    * the Eiffel Tower in Paris
    * St. Basil's Cathedral in Moscow
    * Big Ben and the tower from the Palace of Westminster in London
    * the leaning tower of Pisa
    * the Space Needle in Seattle
    * the Tower Bridge in London
    * the Makkah Royal Clock Tower in Mecca
    * the Gateway Arch in St. Louis
    * Potola Palace in Lhasa, Tibet
    * Westminster Abbey in London
    * Le Mont-Saint Michel
    * the pyramids of Giza
    * Chateau Frontenac in Quebec


### <a name="ramp"></a>Ramp proposal

Optionally, an Impossible City could have:
  * **no stairways**, no stairs, and no steps &mdash; (don't squander floor space)
  * **no elevators** &mdash; (at $100,000 or more each)
  * **no escalators**

In this scenario, the only way to go "upstairs" or "downstairs" in an Impossible City would be by using:
  * flights of **wheelchair ramps**
  * hallway ramps
  * sidewalk ramps
  * bike path ramps

The idea of having **no stairs** and **no elevators** sounds crazy to most people when they first hear it, because it's so different from all the normal buildings and cities that we're used to.

However, if you run the numbers, and run simulations, it turns out that getting rid of elevators and stairs works out just fine. Instead of making it harder to get places, having no elevators makes it **faster** to get between any two random locations. 

The Impossible City **ramp-only** design:
* is faster and more convenient for people in wheelchairs, and people with strollers
* is faster for everybody else too
* works better for delivery robots
* works better after a natural disaster
* takes up less space in the building
  > In the Seagram building (which has 38 floors), the area used for elevators and utility shafts occupies 31 percent of the area of a typical floor.[^bertaud]

* can be built more quickly
* is less expensive to build
* is less expensive to operate
* is less expensive to maintain
* has a smaller carbon footprint
  > "Lifts also use a large amount of energy to run. For buildings that are largely served by lifts, you can add a rough figure of 5 to 15 per cent onto building energy running costs."[^roaf] &mdash; Susan Roaf




### <a name="safety"></a>Safety proposal

An Impossible City could have:
  * **no gas lines**
  * **no telephone poles**
  * **no overhead power lines**

Instead, it would have: 
  * **underground power lines**
  * **underground telephone lines**



















<div class="hr"><a name="1"></a></div>

## <a name="source-material"></a><span class="chapter">Source material, chaper 1</span>

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


### <a name="cars"></a>Car speeds

> "cars in the busiest parts of Manhattan now move just above a jogger's pace, about 7 m.p.h., roughly 23 percent slower than at the beginning of the decade." [^haag]



### <a name="pedestrians"></a>Pedestrian speeds

> "the average human walking speed at crosswalks is about 5.0 kilometres per hour (km/h), or about 1.4 meters per second (m/s), or about 3.1 miles per hour (mph). Specific studies have found pedestrian walking speeds at crosswalks ranging from 4.51 kilometres per hour (2.80 mph) to 4.75 kilometres per hour (2.95 mph) for older individuals and from 5.32 kilometres per hour (3.31 mph) to 5.43 kilometres per hour (3.37 mph) for younger individuals" [^wiki_walking]

* walking speed: 2.17 mph up a 1:12 ADA ramp
* walking speed: 2.6 mph UP or DOWN an 1:12 ADA ramp [^sun]


|---
|       |   | Walking<br>speeds<br>per<br>horizontal<br>distance[^fujiyama] |
| Stair<br>gradient  | Grade | Up stairs | Down stairs | Up stairs | Down stairs |
| (degrees) | (rise:run) | over 50 | age 30 to 50 | over 50 | age 30 to 50
|  :-:  |  :-:  |  :-:  |  :-:  |  :-:  |  :-:  |
|  38.8 |   80:100 | 0.435 m/s | 0.485 m/s | 0.47 m/s  | 0.59 m/s  
|  35.0 |   70:100 | 0.515 m/s | 0.565 m/s | 0.585 m/s | 0.645 m/s 
|  30.5 |   59:100 | 0.58 m/s  | 0.635 m/s | 0.64 m/s  | 0.74 m/s 
|  24.6 |   46:100 | 0.72 m/s  | 0.76 m/s  | 0.80 m/s  | 0.865 m/s 
|  32   | 62.5:100 | 0.41 m/s  | 0.60 m/s  | 0.52 m/s  | 0.60 m/s 
|  27   |   51:100 | 0.43 m/s  | 0.73 m/s  | 0.58 m/s  | 0.73 m/s 
|---

```
tan(27 degrees) = 0.51 => 51% grade = 51 foot rise per 100 foot run

0.73 m/s horizontal on 27 degree stairs => 0.37 m/s vertical = 1.22 feet/sec vertical
```


### <a name="co2"></a>CO2-e emissions

|---
| CO2-e emissions[^bertaud] | Vehicle type
|-:|:-
| grams per passenger km
| 151 | average US car
|  26 | Nissan Leaf in California
|   5 | Nissan Leaf in Sweden
|  67 | New York subway
| 180 | US urban bus
|---



### <a name="noise"></a>Noise

> "...the population in Wuhan is 8.3 million, much greater than that in Sheffield, at 0.6 million. ... For Wuhan, given that the number of vehicles per person is still much lower than that in Sheffield by tenfold ... it is very interesting to note that the average noise levels in all of the sampled areas are lower than those in Sheffield by 2dBA to 11dBA. ... In terms of L<sub>min</sub> and L<sub>90</sub> ... the difference is even greater -- for example, up to 15dBA in the area with a motorway."[^kang] &mdash; Jian Kang









### <a name="density"></a>Density

  |---
  | People per<br>square mile | City | Land area<br>square feet<br>per person 
  |-:|:-|-:|
  |  85,829 | Central Paris[^crawford]                  |   325 | 
  | **78,874** | **Impossible City Proposal**<br>(density of city districts, sans greenbelt)    |   353 |
  |  71,340 | Manhattan, New York[^wiki_manhattan]      |   391 | 
  |  68,376 | J.H.Crawford's _Carfree Cities_ Reference Design<br>(density of city districts, sans greenbelt)[^crawford]  |   408 | 
  |  52,593 | Paris[^wiki_paris]                        |   530 | 
  |  27,751 | New York City[^wiki_new_york_city]        | 1,005 |
  |  18,838 | San Francisco[^wiki_san_francisco]        | 1,480 | 
  |  10,117 | J.H.Crawford's _Carfree Cities_ Reference Design<br>(combined density of city districts **and** greenbelt)[^crawford]  |   2,756 | 
  |  10,101 | Suburban single-family housing[^crawford] | 2,760 | 
  |         | _For more examples of city densities, check out [DensityAtlas.org](http://densityatlas.org/)._ |  | 
  |---
  


<!--
  |---
  | people<br>per<br>mile<sup>2</sup> | region | feet<sup>2</sup><br>per<br>person | land area of cities<br>meters<sup>2</sup><br>per person<br>in 2014
  |-:|-:|:-|-:
  |  55,106 | South and Central Asia                   |   506 |  47[^bertaud]
  |  34,079 | Southeast Asia                           |   818 |  76[^bertaud]
  |  28,461 | Western Asia and North Africa            |   980 |  91[^bertaud]
  |  27,263 | Sub-Saharan Africa                       | 1,023 |  95[^bertaud]
  |  25,900 | Latin America and the Caribbean          | 1,076 | 100[^bertaud]
  |  20,555 | East Asia and the Pacific                | 1,356 | 126[^bertaud]
  |  15,988 | Europe and Japan                         | 1,744 | 162[^bertaud]
  |   6,080 | Land-rich developed countries            | 4,585 | 426[^bertaud]
  |---
-->


### <a name="far"></a>Floor area ratio

  |---
  | FAR<sub>parcel</sub> | FAR<sub>overall</sub> | Place
  |-:|-:|:-
  |     0.3[^bertaud] |        | US suburbs
  |                   |   0.41 | San Francisco
  |                ~  |    1.7 | Proposed Impossible City
  |     3.5[^bertaud] |        | Historical Paris
  | 4 to 10[^bertaud] | 3 to 7[^densityatlas] | Manhattan residential
  |      15[^bertaud] |     10 | Manhattan office buildings
  |      25[^bertaud] |        | Singapore highest FAR
  |                   |        | _For more FAR examples, check out [DensityAtlas.org](http://densityatlas.org/)._ |  | 
  |---


> "urban planners historically focused on residential travel and personal behavior, failing to integrate the movement of goods into their planning." [^wenzel]







## <span class="chapter">Source material, chaper 2</span>

### <a name="bicycles"></a>Bicycles

> We see that bicycles provide a much higher road capacity at speeds below 15 km/h than any other mode of transport.[^bertaud]

> Because of their higher speed and increased comfort, electric bicycles, where they are authorized (as in Chengdu, China), could meaningfully compete with buses or cars as a means of commuting in larger cities.[^bertaud]

> The emergence of small footprint, on-demand, shared vehicles ... will change the way urban transport is organized. The pattern of roads and arterials may also change to adapt to these new modes of urban transport. Instead of concentric traffic on a few high-capacity highways or arterials, numerous smaller low-capacity roads would allow the flexibility required by trips from dispersed origins to dispersed destinations.[^bertaud]

### <a name="small_cars"></a>Small cars

> By contrast, compared to the motorcycle, compact Smart car performance (except for energy use) in terms of road capacity is not much better than that of an ordinary car. ... The width of the vehicle, not its length, is the important parameter to consider when trying to reduce street area consumption.[^bertaud]

### <a name="small_cars"></a>Kinematic range

  * In **San Francisco**, if you are able-bodied and travel by bicycle or public transit, but you do not use a car, then in 30 minutes you can probably get from almost any building in the city to almost any room in any other building in the city. But without a car, there are fairly few places you can get to outside the city limits within 30 minutes. The buildings in San Franicsco have a total of about 540 million square feet of floorspace, and your **KR<sub>30</sub>** might be about **450 million square feet**, which is about 50-thousand-fold higher than your range in Haxby.
  
  * **Wurster Hall** is a building on the campus of the University of California, Berkeley. It's a fairly typical mid-rise building, with a normal mix of offices, meeting rooms (classrooms), and open plan work spaces. Most of the floorspace is in the wider base in the first three floors, but there's a narrower tower that's ten stories tall. The building has a total of about 225,000 square feet of floorspace, and within 2 minutes you can go between almost any two points in the building, so that's a 2-minute Kinematic Range, **KR<sub>2</sub>**, of **225,000 square feet**.
  
  * On the **UC Berkeley campus**, traveling by foot, it takes about 25 minutes to walk between two buildings at opposite ends of the main campus. If it takes another 2 minutes to get from the lobby door of a building to a top-floor room, and vice-versa, that means any two rooms on the whole campus are within a 29-minute range. If the campus has about 10 million square feet of floorspace<sup>[citation needed]</sup>, then your **KR<sub>30</sub>** would be about **10 million square feet**.  

  * In the **US Pentagon building**, it is possible to walk between any two points in less than seven minutes. The Pentagon has 6.6 million square feet of floorspace, so that's a **KR<sub>7</sub>** of **6.6 million square feet**.[^wiki_pentagon] 


### Congestion

> "In a study last year, Inrix estimated that the cost of congestion in the United States alone was $305 billion (USD)" [^turbot]

> "In L.A., nothing concerns locals more than traffic—not personal safety, the cost of living, or even the housing market—according to a 2016 poll by the Los Angeles Times. Drivers there spend an average of 80 hours in gridlock every year, according to a report by Texas A&M University."[^bliss]










## <span class="chapter">Source material, chaper 3</span>

### Affordability

> "Above six storeys, significant extra costs are incurred in sprinkler systems, and after ten storeys, the need for enhanced fire escape provision means that the extra costs can only be recouped if storey heights push up above 15 storeys."[^roaf] &mdash; Susan Roaf

> "For five Melbourne office buildings of the following heights: 3, 7, 15, 42 and 52 storeys, the two high-rise buildings were found to have approximately 60 per cent more energy embodied per unit gross floor area (GFA) in their materials than the low-rise buildings."[^roaf] &mdash; Susan Roaf

|---
| Height<br>in stories | GJ per square meter<br>gross floor area[^roaf] |
|-:|-:|
|  3 | 10.7
|  7 | 11.9
| 15 | 16.1
| 42 | 18.0
| 52 | 18.4
|---

> "In addition, there are higher operation and maintenance costs in taller buildings..."[^roaf] &mdash; Susan Roaf





### <a name="parks"></a>Parks & trees

> "Meyer-Lindenberg is currently tracking how different parts of the city affect our mental wellbeing, using a technique called ecological momentary assessment, in which participants repeatedly report on the environment around them in real time. Various studies have suggested that nature – be that a tree or a park – has an important impact on people’s mental health."[^macdonald]

> "Studies have consistently linked city living with poorer mental health. For example, growing up in an urban environment is correlated with twice the risk of developing schizophrenia as growing up in the countryside."[^macdonald]

> "Mental health is almost uniformly worse in cities... that's just what the data shows," [Andreas] Meyer-Lindenberg says over the phone. "There isn't really a bright side to this."[^macdonald]



### <a name="resiliency"></a>Resiliency

  > "Resiliency is the ability to bounce back better, but also the ability to not have to bounce back as much." 
  > &mdash; Sylvester Wong, Vice President of AECOM[^new-clark]

  > "Because its location and design were deliberately chosen to withstand natural calamities, New Clark City will serve as the government’s continuity hub, disaster and risk recovery center – an alternative capital city in case a disaster strikes Manila"[^new-clark]










## <span class="chapter">Source material, chaper 4</span>

### <a name="growth"></a>Global urban growth

"Half of the urban area that will be needed [by 2050] hasn't been built yet."[^growth]

"Over the next 40 years, the **newly built floor area** in the world is **expected to double**."[^watts]

"We're going to develop more urban area in the next 100 years than currently exists on Earth"[^growth] &mdash; Paul Romer, Nobel prize-winning economist, New York University.

"The amount of floorspace in buildings around the world—currently about **2.5 trillion square feet**—is set to **double by 2060**" &mdash; Brian Bienkowski [^bienkowski]

It is estimated that **by 2050**:
* about **2.5 billion additional people** will live in cities (vs. 2019), with 90% of the uptake in Asia and Africa[^growth]
* **68% of the world's population** will be living in cities (vs. 55% in 2018)[^growth]<sup>,</sup>[^mason]
* about **200 million climate migrants** will settle in new locations. (Forecasts vary from 25 million to 1 billion.)[^migrants]
* **400 million people in India** will migrate to cities[^sharma]
* the **African population will double** from 1.3 billion today to over **2.5 billion** [^forbes]
* there will be at least **nine African "megacities" of 10 million people or more** (and more than two dozen African cities of 5 million or more, about the size of metropolitan Washington), but currently 60 percent of Africa’s city dwellers live in slums [^bloomberg]
* one-third of all of the French Polynesian islands will be submerged[^fast-company]

> "This will be by far the largest migration of human beings to have ever taken place on the planet ... The resulting challenges to the availability of energy and resources and the enormous stress on the social fabric across the globe are mind-boggling ... and the timescales to address them are very short."[^scale] &mdash; Geoffrey West

> "The UN estimates that each year cities across the world will gain more than 72 million new residents."[^lutter]

> "averaged over the next thirty-five years, about a million and a half people will be urbanized each week ... the equivalent of another New York metropolitan area [every two months]"[^scale]

> **120 "new cities"** are currently being built, **in 40 countries**.[^haas] These developments are frequently called "new cities", although often they are more like new suburbs or new satellite neighborhoods of existing cities, rather than brand new cities in their own right.

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

> "There are billions of people living on coastlines that are going to be flooded. It’s going to be worse and worse and worse year by year and they are going to have to move eventually, and where are they going to move to? ... we're going to have to deal with that on a large scale" &mdash; Dr. Tom Goreau, president of the Global Coral Reef Alliance.[^shepard]

> "it has been estimated that it’s going to cost the USA alone around $400 billion over the next two decades in sea level rise damage control"[^shepard]


### Lost opportunities
> "The San Francisco metro area [the counties of San Francisco, Alameda, Marin, Contra Costa, and San Mateo] is the third most valuable region in America based on the value of its residential real estate. The area's total residential real estate value hit an astonishing $1.3 trillion and it's outranked only by the Los Angeles and New York metro areas, with total residential real estate values of $2.2 trillion and $2.6 trillion, respectively." ... "San Francisco is one of three cities nationwide that can claim a market value higher than Apple Inc.'s $1 trillion."[^hoeven]



### <a name="precident"></a>"New city" greenfield developments

More than **120 new cities** are currently being built in 40 nations around the world[^growth], and 11,000 new buildings are built every day, meaning **4 million new buildings a year** [^metabuild]. (These developments are frequently called "new cities", although often they are more like new suburbs or new satellite neighborhoods of existing cities, rather than brand new cities in their own right.)

  * **Nkwashi**, in Zambia, being built by Thebe Investment Management, is expected to house up to 100,000 people.[^mason]
  * **Tatu City**, in Kenya, being built by Rendeavour, is planned for 150,000 residents.[^mason]
  * **Forest City**, in Malaysia (700,000 residents) 
  * **Enyimba Economic City**, in Nigeria (1.5 million residents)
  * and more than 100 others...

> "Neom is best described as a $500 billion ... plan for a 10,000 square mile area"[^lutter]

> "New Cairo, ... when completed, it could house as many as 5 million residents"[^lutter]

> "Forest City is a $100 billion new city development which will house 700,000 residents when completed. Forest city is a 5600-acre development."[^lutter]


### New York land value

> "At 305 square miles, New York City makes up only 0.008% of the total land area of the U.S., yet its $1.5tr of housing value is about 5% of the Nation-wide total. Only four states are worth more than New York City, one of which is New York State."[^metrocosm]

> "Manhattan‘s housing alone is worth about $733bn, which would make it the 14th most valuable state in the country. Manhattan measures only about 20 square miles, 7.5% of New York City."[^metrocosm]

> "What I found most striking of all was the value of some Manhattan neighborhoods. The Upper East Side, which occupies less than one square mile, has an astounding $96bn of housing value. That places it above Staten Island and the Bronx as well as above six states: New Hampshire, North Dakota, South Dakota, Vermont, Wyoming, and Alaska."[^metrocosm]

> "The developable land in Manhattan—excluding parks, roads, and highways—was worth between $1.54 and $1.95 trillion, for an average of $1.74 trillion"[^manhattan]

* From 1950 to 2015, the value of Manhattan land grew at an annual rate of 5.5 percent beyond inflation[^manhattan]








## <span class="chapter">Source material, chaper 5</span>

### <a name="cost"></a>Greenfield development vs. retrofitting

> "when planned, built, and governed well, cities can be massive agents of positive change," ... "They can be catalysts for inclusion and powerhouses of equitable economic growth. They can help us protect the environment and limit climate change. That is why we need a new vision for urbanization." &mdash; UN Secretary-General Ban Ki-moon [^totaro]

> "Our biggest urban problems today—growing inequality, rampant gentrification, housing unaffordability, and increasing segregation—all have roots in the staggering cost of urban land."[^manhattan]

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


### <a name="construction-costs"></a>Construction costs

> "the price of construction for an apartment fully equipped with kitchen and bathrooms may cost several thousand US dollars per square meter (about US$2,500 per square meter in New York in 2013 for residential buildings three to seven stories tall)."[^bertaud]

> "In the lowest-income countries, where construction is the cheapest, households would need to be able to afford at least US$6,000 for a studio of 12 square meters; US$6,000 is the global market commodity price for the basic construction materials of concrete and steel required to build 12 square meters."[^bertaud]

> "San Francisco has the world's second-highest construction costs... The city's average construction costs of $330 per square foot was second only to New York, according to a study last year by Turner and Townsend, a construction consultant. Apartments cost around $425,000 per unit to build." [^li]

> "New York and San Francisco topped the list of the most expensive construction markets, costing respectively an average of $354 and $330 per square foot to build. Seattle, which faces many of the same labor market and housing supply pressures as San Francisco, came in at $280 per square foot."[^reid]


### <a name="funding"></a>Funding for new city projects

> "Cities generate roughly 80% of global GDP and are home to more than half of the world's population today, a share that the United Nations projects will reach two-thirds by 2050," the report said. About 40% of the population lives within 100 kilometers of a coast, and one in 10 people live in areas less than 10 meters above sea level, it said. [^khan]


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



### Land value capture

There are established public-sector mechanisms for funding development projects, such as Tax Increment Financing (TIF).

> "Portland, Oregon, currently dedicates about 40 percent of its TIF revenues to affordable housing. Over nine years, the program generated nearly **a quarter of a billion dollars for affordable housing**..."[^schneider]

> "The $6 billion Lincoln Yards development in Chicago ... stands to receive **$1.3 billion in TIF funding**"[^schneider]



> "Value capture is a way to generate revenue by recouping a portion of the gains 
> in the value of land that result from improvements of public transportation. ...
> Common value capture mechanisms include:"[^xu]
> ~ Leasing development rights or selling land. (e.g. Hong Kong)
> ~ Land Value Tax.
> ~ Tax Increment Financing (TIF). (e.g. New York)

> "To conclude from the above literatures, value capture models are applicable 
> to cities that have a good coordination of land use, city planning and 
> economic development."[^xu]

> "Second, it should be able to acquire land at a favorable price, which will 
> minimize the cost and maximize the profit from future land transition."[^xu]


> "despite this potential ... value capture ... doesn't work in areas that are 
> already developed. ... undeveloped area provide the most room for growth."[^jaffe]


> "Hong Kong’s public transit development method, which is well known as a distinctive example of transit value capture. ... Hong Kong is one of the few cities in the world where public transport makes a profit."[^xu]

> "In terms of land attribute, all land in Hong Kong is state property and the only land tenure is leasehold. The government of Hong Kong is responsible for land management, development, and its lease to private entities, based on China’s Basic Law passed in 1990. Private developers bid to lease land with a general 50 years term."[^xu]

> "The state leasehold system captures value from four major aspects: initial land auction, lease modification, lease renewal, and land rent collection. Among the four, initial land auction has been the major source of lease revenue, accounting for about 75 percent of government's total land income (Hong, 1998)."[^xu]

> "During the whole process, MTR is functioning as the master planner. It creates a development layout plan, monitors development quality, and manages the lease and sales of completed properties. It is a bridge between the government and developers. It sets clear rules to multiple stakeholders, making the partnership smooth and efficient."[^xu]

> "One reason that projects like Tsing Yi Station come into success is that the land use integration is evaluated at the master planning stage by MTR (Tang, Chiang, Baldwin & Yeung, 2004). This magnifies the interaction between railway and property development."[^xu]

> "Hong Kong's strategy can be applied in cities where government owns the land."[^xu]

> "Thirdly, the planning of public transportation requires multiple levels of government and agencies to work together. It is important to form a good collaboration between the different development stages, including land acquisition, planning, construction, operation, and property management. In Hong Kong, for example, MTR as a single agency is responsible for the whole development cycle. The process is more efficient, because it saves additional administrative cost, and there is only one principle from beginning to end. For New York, however, as MTA is only responsible for railway construction and operation, and it has no right of land use, the capability of capturing land value is to some extent undermined."[^xu]

"Bartholomew and Ewing’s (2010) study indicates transit accessibility, walkability, and environment quality can be capitalized into real estate prices. The existence of high walkability and mixed land use types are likely to increase land values independent of transit accessibility."[^xu]

"Other factors related to the value generated from public transportation include the service quality, the extent of network, and the ticket price. Andersson (2010) conducted a research about the high speed rail in Taiwan, and finds out that it has little impact on land values due to the high ticket price (A monthly ticket can take up to 70% of the median monthly wage in Taiwan). It is difficult to capitalize expensive services into land values."[^xu]

"Hong Kong is a small island city with an area of 1104 square kilometers. To date, the city has a population of 7.1 million, and is projected to reach 8.6 million by 2026 (HK Census and Statistics Department, 2014)."[^xu]

"Zoning regulations allow special FARs in key station areas to attract private investments and comprehensive development."[^xu]

> "Corner lots are significantly more valuable than mid-block lots, according to the study, and lots in close proximity to Broadway, which runs the length of the island, also have higher values."[^manhattan]










## <span class="chapter">Source material, additional</span>


> "More recent data, however, reveal substantial urban‐rural fertility gaps (i.e. of one child or more per woman) that tend to be wider at more advanced stages of the fertility transition" [^lerch]

> "In the full sample of countries, rural fertility is almost 20 percent higher than the urban level on average in the pre‐transitional cohorts. ... The ratio increases sharply in the first 20 transition cohorts to 40 percent, stabilizing at this level in the subsequent 10 cohorts. After 30 cohort years have elapsed since the transition onset, the average rural‐urban ratio has dropped monotonically down to 1.23 (in the 55th transition cohort)." [^lerch]

  > "Double the size of a city and on average you'll find twice as many businesses. The proportionality constant is 21.6, meaning that there is approximately one establishment for about every 22 people in a city, regardless of the city size. Or to put it slightly differently, on average a new workplace is created each time the population of a city increases by just 22 people. ... on average, there are only about 8 employees for every establishment, again regardless of the size of city."[^scale] &mdash; Geoffrey West


### <a name="pricing"></a>Congestion pricing

> In their 2009 book, aptly title Mobility First, Sam Staley and Adrian Moore describe in detail the cross-disciplinary reforms in road and urban transport design and in road pricing, among other things, that would be required to maintain mobility in cities in the twenty-first century.[^bertaud]

> The rent charged should vary with the time of day, the location, the area, and the length of time the road is used. The rent charged for roads should be similar to the fares charged by airlines to passengers or the room rates charged by hotels, except that the rate would not be for a fixed 24 hours but for the number of minutes the roads are actually used.[^bertaud]

### <a name="freight"></a>Freight

> "And New York City, where more than 1.5 million packages are delivered daily..." [^haag]

> In New York City, "Delivery trucks operated by UPS and FedEx double-park on streets and block bus and bike lanes. They racked up more than 471,000 parking violations last year, a 34 percent increase from 2013." [^haag]

> "The main entryway for packages into New York City, leading to the George Washington Bridge from New Jersey, has become the most congested interchange in the country. Trucks heading toward the bridge travel at 23 miles per hour, down from 30 m.p.h. five years ago." [^haag]

> "The average number of daily deliveries to households in New York City tripled to more than 1.1 million shipments from 2009 to 2017, the latest year for which data was available, according to the Rensselaer Polytechnic Institute [Center of Excellence for Sustainable Urban Freight Systems](https://coe-sufs.org/wordpress/). ... Households now receive more shipments than businesses." [^haag]

> "And it could be just the beginning. Just 10 percent of all retail transactions in the United States during the first quarter of 2019 were made online, up from 4 percent a decade ago, according to the Census Bureau." [^haag]

> "About 15 percent of New York City households receive a package every day, according to the Sustainable Urban Freight Systems center at Rensselaer." [^haag]


### <a name="notes"></a>Notes

**TODO:** include on this web page some animated images of traffic simulations for the Impossible City design, maybe somewhat like the SUMO simulation output images on this page:
[sidewalk-talk](https://medium.com/sidewalk-talk/https-medium-com-sidewalk-talk-street-sim-33da7e1a8ffb)














<div class="hr"><a name="1"></a></div>

## <a name="references"></a><span class="chapter">References</span>


<!-- References, Chapter 1 -->

[^alter]: ["6 month report: My e-bike ate my car"](https://www.treehugger.com/bikes/6-month-report-my-gazelle-e-bike-ate-my-car.html). Lloyd Alter, _TreeHugger_. 1 November 2019.

[^bertaud]: _[Order without Design](https://mitpress.mit.edu/books/order-without-design): How Markets Shape Cities_, by Alain Bertaud

[^gsdg]: ["Global Street Design Guide"](https://nacto.org/publication/global-street-design-guide/). _National Association of City Transportation Officials (NACTO)_.

[^nacto]: ["Blueprint for Autonomous Urbanism"](https://nacto.org/publication/bau2/), Second Edition. _National Association of City Transportation Officials (NACTO)_.

[^nycdot]: ["New York City Mobility Report"](http://www.nyc.gov/html/dot/downloads/pdf/mobility-report-2018-screen-optimized.pdf), June 2018. _NYC Department of Transportation_.

[^speed-limits]: ["Manhattan Speed Limits"](https://www1.nyc.gov/html/dot/downloads/pdf/current-pre-vision-zero-speed-limit-maps.pdf).  _NYC Department of Transportation_.

[^kang]: ["Sound Environment: High- versus Low-Density Cities"](https://books.google.com/books?id=oThZvLKMnCYC&pg=PA163&lpg=PA163&dq=Sound+Environment:+High-+versus+Low-Density+Cities&source=bl&ots=cQs-vnAVTP&sig=ACfU3U17dCObgKhnwADmNIqxKvDQW8NUGA&hl=en&sa=X&ved=2ahUKEwjg_4mKuPjoAhVTHzQIHQPBB8QQ6AEwAHoECAoQAQ#v=onepage&q=Sound%20Environment%3A%20High-%20versus%20Low-Density%20Cities&f=false), by Jian Kang, Chapter 12 of ["Designing High-Density Cities"](https://www.amazon.com/Designing-High-Density-Cities-Environmental-Sustainability/dp/1844074609), edited by Edward Ng

[^fujiyama]: ["An Explicit Study on Walking Speeds of Pedestrians on Stairs"](https://discovery.ucl.ac.uk/id/eprint/1243/1/2004_21.pdf), Taku Fujiyama and Nick Tyler, _University College London_.

[^wiki_walking]: ["Walking"](https://en.wikipedia.org/wiki/Walking). _Wikipedia_.

[^haag]: ["1.5 Million Packages a Day: The Internet Brings Chaos to N.Y. Streets"](https://www.nytimes.com/2019/10/27/nyregion/nyc-amazon-delivery.html). Matthew Haag and Winnie Hu, _New York Times_. 27 Oct 2019.

[^sun]: ["The influence of surface slope on human gait characteristics: a study of urban pedestrians walking on an inclined surface"](https://www.tandfonline.com/doi/abs/10.1080/00140139608964489). JIE SUN, MEGAN WALTERS, NOEL SVENSSON & DAVID LLOYD, _Ergonomics_ Volume 39, 1996 - Issue 4

[^wenzel]: ["How the Urban Freight Lab seeks to fix the last 50 feet of shipping"](https://www.greenbiz.com/article/how-urban-freight-lab-seeks-fix-last-50-feet-shipping). Elsa Wenzel, _GreenBiz Group_. 15 October 2019.











<!-- References, Chapter 2 -->

[^google_eie]: [Environmental Insights Explorer](https://insights.sustainability.google/places/ChIJIQBpAG2ahYAR_6128GcTUEo/transportation). _Google_. 2018.

[^growth]: ["Should we build cities from scratch?"](https://www.theguardian.com/cities/2019/jul/10/should-we-build-cities-from-scratch). _The Guardian_. 10 July 2019.

[^scale]: [_Scale_](https://www.penguinrandomhouse.com/books/314049/scale-by-geoffrey-west/), by Geoffrey West. 2018.

[^velotopia]: [_Velotopia_](https://www.nai010.com/en/publicaties/velotopia/130528), by Steven Fleming. 2017

[^wiki_pentagon]: ["The Pentagon"](https://en.wikipedia.org/wiki/The_Pentagon). _Wikipedia_.

[^bliss]: ["Navigation Apps Changed the Politics of Traffic"](https://www.citylab.com/transportation/2019/11/future-of-transportation-traffic-navigation-apps-google-maps/601684/). Laura Bliss, _City Lab_. 12 November 2019.

[^turbot]: ["Living Together, Happier Together"](https://newcities.org/blog-living-together-happier-together/). Sébastien Turbot, _NewCities_. 20 March 2019.

[^kneebone]: ["The growing distance between people and jobs in metropolitan America"](https://www.brookings.edu/wp-content/uploads/2016/07/Srvy_JobsProximity.pdf). Elizabeth Kneebone and Natalie Holmes, _Metropolitan Policy Program at Brookings_. July 2016.





<!-- References, Chapter 3 -->

[^carl_walker]: ["Parking Structure Cost Outlook for 2017"](https://denver.streetsblog.org/wp-content/uploads/sites/14/2017/10/2017-Cost-Article.pdf). Gary Cudney, Carl Walker.  

[^gadepalli]: "Even though women comprise nearly half of the population, it is surprising they account for less than one in five trips made in Indian cities." ["Delhi Will Improve When Women Get to Move"](https://newcities.org/delhithe-big-picture-will-improve-women-get-move/). Shreya Gadepalli, _NewCities_. 8 March 2019.

[^gonzalez]: "Evidence from Argentina shows that on average men and women’s commute time is roughly the same, but women travel at slower speeds and cover shorter distances." ["Transport is Not Gender Neutral"](https://newcities.org/the-big-picture-transport-is-not-gender-neutral-womens-mobility-and-accessibility-for-better-economic-opportunities/) Karla Dominguez Gonzalez, _NewCities_. 8 March 2019.

[^mccasland]: ["Cities Foster Equity by Improving Urban Mobility for Women"](https://newcities.org/the-big-picture-cities-foster-equity-by-improving-urban-mobility-for-women/). Hannah McCasland, _NewCities_. 8 March 2019.

[^new-clark]: ["Resilient Growth: Building a Resilient City in the Philippines"](https://newcities.org/the-big-picture-resilient-growth-building-resilient-city-philippines/). _NewCities_. 2019.

[^macdonald]: ["Urban living makes us miserable. This city is trying to change that"](https://mosaicscience.com/story/urban-living-city-mental-health-glasgow-cities-happiness-regeneration/). Fleur Macdonald, _Mosaic_. 15 October 2019.

[^levinson]: ["21 Solutions to Road Deaths"](https://transportist.org/2019/10/02/21-solutions-to-road-deaths/). David Levinson, _Transportist_. 2 Oct 2019.

[^ng]: ["We ran traffic simulations on our people-first street designs. Here’s what we found"](https://medium.com/sidewalk-talk/https-medium-com-sidewalk-talk-street-sim-33da7e1a8ffb). Willa Ng, _Sidewalk Labs_. 9 September 2019.

[^grabar]: ["The Hyperloop and the Self-Driving Car Are Not the Future of Transportation"](https://slate.com/technology/2019/10/future-of-transportation-bus-bike-elevator.html). Henry Grabar, _Slate.com_. 30 Oct 2019.

[^kamiya]: ["Sex and cycling: How bike craze aroused passions in 1890s San Francisco"](https://www.sfchronicle.com/bayarea/article/Sex-and-cycling-How-bike-craze-aroused-passions-14544576.php#photo-18459519). Gary Kamiya, _San Francisco Chronicle_. 18 Oct 2019.

[^road-safety]: ["HELPING TO SAVE LIVES THROUGH PROVEN INTERVENTIONS THAT REDUCE ROAD TRAFFIC FATALITIES"](https://www.bloomberg.org/program/public-health/road-safety/). _Bloomberg Philanthropies_

[^roaf]: ["The Sustainability of High Density"](), by Susan Roaf, Chapter 3 of ["Designing High-Density Cities"](), edited by Edward Ng.






<!-- References, Chapter 4 -->

[^un-desa]: ["68% of the world population projected to live in urban areas by 2050, says UN"](https://www.un.org/development/desa/en/news/population/2018-revision-of-world-urbanization-prospects.html). _United Nations, Department of Economic and Social Affairs_. 16 May 2018.

[^ontariotech]: ["GCIF Working Paper No. 4: Population predictions of the 101 largest cities in the 21st century."](https://sites.ontariotechu.ca/sustainabilitytoday/urban-and-energy-systems/Worlds-largest-cities/population-projections/city-population-2050.php). Hoornweg & Pope. 

[^mgi]: ["Urban world: Mapping the economic power of cities"](https://www.mckinsey.com/~/media/McKinsey/Featured%20Insights/Urbanization/Urban%20world/MGI_urban_world_mapping_economic_power_of_cities_full_report.ashx). _McKinsey Global Institute, McKinsey & Company_. March 2011.

[^savills]: ["8 things to know about gloval real estate value"](https://www.savills.com/impacts/market-trends/8-things-you-need-to-know-about-the-value-of-global-real-estate.html). _Savills Impacts_. July 2018.

[^facc]: ["Key Facts"](https://www.faccsf.com/info/key-facts.html). _French American Chamber of Commerce_.

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

[^hoeven]: ["What's worth more: All of San Francisco's residential real estate or Apple Inc.?"](https://www.bizjournals.com/sanfrancisco/news/2018/08/29/value-sf-real-estate-homes.html). Emily Hoeven, _San Francisco Business Times_. 29 August 2018.

[^metrocosm]: ["A Striking Perspective on New York City Property Values"](http://metrocosm.com/new-york-city-property-values-in-perspective/). _Metrocosm_. 24 June 2015.







<!-- References, Chapter 5 -->

[^wiki_citycenter]: ["CityCenter"](https://en.wikipedia.org/wiki/CityCenter). _Wikipedia_.

[^bertaud]: _[Order without Design](https://mitpress.mit.edu/books/order-without-design): How Markets Shape Cities_, by Alain Bertaud

[^li]: ["Why San Francisco has the second-highest construction costs in the world"](https://www.bizjournals.com/sanfrancisco/news/2018/01/24/sf-construction-costs-2nd-highest-housing-crisis.html). Roland Li, _San Francisco Business Times_. 24 Jan 2018

[^reid]: ["Perspectives: Practitioners Weigh in on Drivers of Rising Housing Construction Costs in San Francisco"](http://ternercenter.berkeley.edu/uploads/San_Francisco_Construction_Cost_Brief_-_Terner_Center_January_2018.pdf). Carolina Reid and Hayley Raetz, _Terner Center for Housing Innovation_. January 2018.

[^khan]: ["Goldman Sachs released a 34-page analysis of the effects of climate change. And the results are terrifying."](https://markets.businessinsider.com/news/stocks/goldman-sachs-climate-change-threatens-new-york-tokyo-lagos-cities-2019-9-1028552494). Yusuf Khan, _Markets Insider_. 25 September 2019.

[^free-private-cities]: [Free Private Cities](https://freeprivatecities.com/en/concept/)

[^jaffe]: ["Why more big cities should give value capture a chance"](https://medium.com/sidewalk-talk/why-more-big-cities-should-give-value-capture-a-chance-b9c4cfac9768). Eric Jaffe, _Sidewalk Talk_. 6 March, 2020.

[^xu]: ["Under What Circumstances Will Land Value Capture Work to Finance Public Transit?"](https://academiccommons.columbia.edu/doi/10.7916/D8DF6QC4). Yidan Xu, _Columbia University Libraries, Academic Commons_. May 2015.

[^weyl]: ["Depreciating licenses"](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=2744810). E. Glen Weyl & Anthony Lee Zhang. 24 January 2018.

[^hoyt]: ["Making apartments more affordable starts with understanding the costs of building them"](https://www.brookings.edu/research/making-apartments-more-affordable-starts-with-understanding-the-costs-of-building-them/). Hannah Hoyt and Jenny Schuetz, _Brookings.edu_. 5 May 2020
  




<!-- References, Hypothetical locations -->

[^wiki_projections_of_population_growth]: ["Projections of population growth"](https://en.wikipedia.org/wiki/Projections_of_population_growth). _Wikipedia_.




<!-- References, Impossible City design summary -->

[^dickey]: ["Ex-Uber exec launches startup to autonomously reposition electric scooters and bikes"](https://techcrunch.com/2019/10/15/ex-uber-exec-launches-startup-to-autonomously-reposition-electric-scooters-and-bikes/). Megan Rose Dickey, _TechCrunch_. 15 October 2019.

[^quirk]: ["Outside the box truck: Innovations in delivery that could change our cities"](https://medium.com/sidewalk-talk/outside-the-box-truck-innovations-in-delivery-that-could-change-our-cities-a7c2170d8f9b). Vanessa Quirk, _Sidewalk Talk_. 13 Sept 2018.



<!-- References, Density -->

[^crawford]: _[Carfree Cities](http://www.carfree.com/book/)_, by J.H. Crawford

[^densityatlas]: ["Manhattan, Grand Street Neighborhood"](http://densityatlas.org/casestudies/profile.php?id=121). _Density Atlas_.

[^wiki_manhattan]: ["Manhattan"](https://en.wikipedia.org/wiki/Manhattan). _Wikipedia_.

[^wiki_new_york_city]: ["New York City"](https://en.wikipedia.org/wiki/New_York_City). _Wikipedia_.

[^wiki_paris]: ["Paris"](https://en.wikipedia.org/wiki/Paris). _Wikipedia_.

[^wiki_san_francisco]: ["San Francisco"](https://en.wikipedia.org/wiki/San_Francisco). _Wikipedia_.




<!-- References, Rules of thumb -->

[^florida]: ["Why U.S. Tech Inventors Are So Highly Clustered"](https://www.citylab.com/life/2019/10/technology-inventions-where-work-patents-agglomeration-data/599089/). Richard Florida, _CityLab_. 1 October 2019.






<!-- References, Effective altruism -->

[^lerch]: ["Fertility Decline in Urban and Rural Areas of Developing Countries"](https://onlinelibrary.wiley.com/doi/full/10.1111/padr.12220). Mathias Lerch. 19 December 2018.





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

