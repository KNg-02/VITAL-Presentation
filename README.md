<p align="center" width="100%">
    <img width="33%" src="https://www.vital.gov.sg/images/general/logo.png">
</p>

<h1 align="center">VITAL Document Inventory Management Report</h1>

<h2 align="center">Project Background</h2>

<p>
  VITAL, a government-affiliated agency under the Ministry of Finance, 
  who has a department known as the "Scan Hub" to handle documents, provided by all sorts of agencies from their respective vendors, 
  such as personal particulars, before digitizing them into databases and then returning said documents to their agency of origin.
<p>
    
<p>
  Due to the many agencies that provide said documents, followed by the high amount of such altogether,
  consistent and smooth management of the Scan Hub's document inventory is crucial to meet deliverable timelines effectively.
  Otherwise, undigitised and unreturned documents may continuously pile up, resulting in demands unable to be met, 
  and resources being strained as insufficient resources are present to handle them in general, while more documents continue to be delivered.
</p>

<p>
  This project uses a dataset documenting the amount of documents received (<b>78530</b>), returned (<b>32992</b>) and digitised (<b>25774</b>) per agency (<b>37</b>)/vendor (<b>8</b>) across the years of 2017 - 2022. 
  Its analysis demonstrates a clear effort to be as consise as possible but still meaningful to the company, via narrowing down key agencies that are the source of the highest amount of undigitised and unreturned documents, to be tackled first before providing suggestions in order to do so, which can be applied to other agencies retroactively in the future. 
</p>

<h2 align="center">Insights Deep-Dive</h2>
<h3 align="center">Overwhelming increase in received documents and incomplete work from 2021 and 2022</h3>

<p align="center" width="100%">
    <img width="100%" src="https://i.imgur.com/5sB1DUU.png">
</p>

<p>It was decided to start with a line graph to display the trend of document management across 2017 - 2022, allowing us to immediately get a top-level overview of the amount of work complete against received ones over the five years across six categories, and then proceed through fixing given year(s) of note.</p> 
    
<p>Shockingly, between years <b>2021 and 2022, a massive spike of received documents occurred, followed by a huge gap of unreturned/undigitised documents underneath that failed to keep up with them</b>.</p> 
    
<p>Given how 2017 - 2020 were relatively stable, this event disrupted the fairly consistent management of documents, prompting us to immediately focus efforts on these two points in time.</p>

* <b>Major increase in received:</b>
    * Went up to 28930 (2021) followed by 31748 (2022) from 10849 in 2020.
    * Had a 166% raise from 2020 to 2021, then a 9% raise from 2021 to 2022.

* <b>Inverse decline in returned/digitised:</b>
    * 7154 (24% done) and 12566 (43%) in 2021.
    * Worsened in 2022 by declining further in both categories while the recieved documents rose, with 1904 (5%) and 4525 (15%).

 <p>This glaring discrepancy immediately signals where our intervention efforts should focus.</p>

<b>Stand-out source of the overwhelming mismanagement of documents</b>

<p>Breakdown of document management (2021)</p>
<p align="center" width="100%">
    <img width="100%" src="https://i.imgur.com/capqDqD.png">
</p>

<p>Breakdown of document management (2022)</p>
<p align="center" width="100%">
    <img width="100%" src="https://i.imgur.com/9GUgM1W.png">
</p>

<p><b>Agency 0 was found to be the biggest source of documents between the two years</b>, followed by a high number of undigitised and unreturned amounts within the timeframe through itself, causing the gap in our trends.</p> 
    
<p>This is shown through the given percentage breakdown:</p>

<b>Received documents:</b>

* 20021/28930 (69% received in 2021)
* 25294/31748 (79% received in 2022)

<b>Poor completion rates:</b>

* 7520/20021 (37% digitised within Agency 0 in 2021)
* 2034/20021 (10% returned within Agency 0 in 2021)
* Worse still, it had <b>0 digitised or returned documents in 2022</b>.
