---
layout: post-map
title:  "Meg as a Rural Public Health Nurse"
author: anna
categories: [ Meg ]
image: assets/images/meg-resume.jpg
---

For this story, I want to turn my attention to Aunt [Meg]({{site.baseurl}}/meg), a lifelong public health nurse--a fact I know, in part, because I have a copy of her resume. The carefully typewritten document "from: Margaret E. Newman, R.N." carries the title "Memorandum of Public Health Training and Experiences" and lists Meg's public health education and work experience, with details about her responsibilities and achievements in each position. Meg had first trained in nursing in the early 1900s and worked as a private nurse for a family in the Waynesboro area before moving to New York City to work for the Henry Street Settlement House Visiting Nurse Service, an experience that I will return to in another post. For this post, however, I want to skip ahead--to the three years that Meg worked as a rural public health nurse in Frederick County, Maryland.

According to her resume, from 1924 to 1927, Meg was a Senior Nurse in the Frederick County Public Health Association, and during this time, she:

>Introduced the Sheppard-Towner work and School Health Inspection in the county. Developed Tuberculosis, Mental Health and Dental clinics. Held Child Health Conferences in every city, town and village in the county.

As I started researching Meg's time working in Frederick County, the most valuable sources I found were newspaper articles, which documented her contributions to improving the public's health in many tiny towns scattered throughout western Maryland. To chart Meg's travels throughout the county, I created a custom Google Map, with markers representing each public health event Meg was involved in, as documented in the newspapers.

**Key**: *blue = health clinic; yellow = general visit; green = health talk; purple = school inspection; orange = professional meeting; pink = social engagement*

<p><div id="map" class="map leaflet-container" style="height: 500px; position:relative;"></div>

  <script>

  var map = L.map('map').setView([39.64, -77.72], 9);

  L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png',
    {
      attribution: '&copy; <a href="https://www.openstreetmap.org/copyright">OpenStreetMap</a> contributors',
      maxZoom: 17,
      minZoom: 5
    }).addTo(map);

    $.getJSON("megdata.geojson",function(data){
    // add GeoJSON layer to the map once the file is loaded
    L.geoJson(data).addTo(map);
  });

  </script></p>

The map shows that in Meg's first full year as a public health nurse, she mainly devoted her efforts to the northern section of Frederick County, which is confirmed by a Frederick News article from March 10, 1925:

>On December 1, Miss Margaret E. Newman was placed in charge of small towns in the northern district, and makes the third nurse engaged in local work. This district includes Emmitsburg, Thurmont, Hauvers, Creagerstown, Lewistown, and Catoetin, the remainder of the county being in charge of Miss Wagner.

In late 1925, Maude Wagner, the other rural public health nurse, resigned, and Meg took over her position. After that point, the map shows that Meg began traveling more throughout the southern part of the county.

To better understand the scope of Meg's activities, I used color coding to categorize each event marked on the map. (See key beneath the map.) By far, the most frequent activity documented in the newspaper articles is health clinics. As detailed in the accounts of the clinics, doctors examined the patients, while the nurses performed more of an educational role. At a clinic held on August 21, 1925, in Wolfsville, Meg gave "directions and consultation" to mothers in attendance:

>Miss Newman, in assisting mothers with the care of their children, pointed out the importance of taking preventive measures in regard to all physical ailments, offered specific advice in each case, distributed feeding lists and other material, and aided generally in the promotion of better health among persons of that locality.

In addition to this health clinic work, Meg was involved in a range of other activities intended to improve the public health, including conducting school inspections and giving health talks to local organizations. Meg delivered one such talk at a special meeting of the Parent-Teachers' Association of the Adamstown school on October 13, 1926, succinctly described in the newspaper account as "an interesting health address." As a public health nurse, Meg was responsible not only for dispensing care, but for informing the public about health issues and working with local organizations, such as parent-teacher associations or women's clubs, to coordinate public health events and services.

The map and collection of newspaper articles form a history of Meg's almost three years working as a rural public health nurse in Frederick County, but there is one story that they haven't uncovered, and it lies in the last line of Meg's resume description of her accomplishments in Frederick County:

>With the aid of The National Negro Health Circle, New York City, and individual sponsors in Frederick Co. placed first colored rural public health nurse in Maryland.

In the newspapers I had collected, there were a few mentions of health care provided to people of color in Frederick County, and I returned to these clippings to search for clues.

The first article gave an account of "Negro Health Week," which took place on April 4-10, 1926. During this week, the public health nurses, including Meg, examined all the children of color in city and county schools, finding that out of the 813 examined, 665 had "physical defects." These defects included "decayed teeth," "enlarged nostrils," "eye strain," "undernourished," "not vaccinated," "nasal obstructions," and "defective hearing."

>“The results of the work accomplished this week,” stated Dr. Kefauver, “show that there is a great quantity of Public Health Work to be done among the negroes of Frederick County, especially with those having tuberculosis."

What strikes me about this newspaper account is not the range and severity of the "defects" noted in the African American children, but what it reveals about the other clinics that Meg assisted with and that were documented in the Frederick newspapers: they were only for white people. Hidden behind the statistics of patients treated and descriptions of health advice given was the doctrine of "separate but equal" that reigned in 1920s Maryland.

As I read on, I saw that there were attempts to improve health care services being offered to people of color in Frederick County:

>Miss Katherine Scully, health nurse, has succeeded in having five colored girls accepted as prospective nurses at the Henryton Colored Sanitorium, near Sykesville. ... These will be the first from Maryland to enter there in such capacity, it was understood, and is hoped by Miss Scully to have constructive work done among the colored element here by some of these girls when they have completed the course of three years duration.

This article presented some evidence that the county was working towards a change in health care for African Americans--educating African American women to be public health nurses, eventually to serve in the county. But, this didn't solve the mystery of the identity of the first African American rural public health nurse in Maryland.

I returned to the newspaper database, searching the Maryland newspapers for mentions of the National Negro Health Circle. This brought up an article from the November 2, 1926, issue of the Frederick *News*:

>Health activities among the colored people of Frederick have begun with the arrival in this city Monday of Elizabeth Porter, colored health executive of the National Health Circle, New York City. She will remain here for a year as an experiment in health work among local colored persons.

The new health nurse, the article stated, was going to be paid by the National Health Circle, but her expenses would be covered by "local colored persons who recently held a mass meeting for the purpose of inaugurating the movement here." In her resume, Meg had also referenced these "individual sponsors in Frederick Co.," so it appears that the county public health association, while helping to place Elizabeth Porter in Frederick, did not provide any financial support for her work. The article also announced that Porter's office would be located in the basement of the Asbury M.E. Church in Frederick, and that this would be "where clinics and all work connected with her duties here will take place." And sure enough, just a few weeks later, the *News* carried an account of a clinic, "for colored people, [which] was held at Asbury M.E. church under Dr. O'Neil of Henrytown, assisted by Miss Katherine Scully. Quite a number of persons of the county appeared for examination." On the same day, another clinic was held "under Dr. John M. Nicklas, Baltimore, assisted by Miss Margaret Newman, health nurse. At this clinic fourteen persons were examined, eight were new cases and six were re-examinations." (I wonder how many more people are represented by "quite a number" than the fourteen who attended the clinic for whites.)

These events in Frederick County in the mid-1920s were part of a larger, emerging movement for African American health that had begun a decade earlier, in 1915, when Booker T. Washington launched the National Negro Health Week. Wrote Susan Smith in *Sick and Tired of Being Sick and Tired: Black Women's Health Activism in America, 1890-1950*:

>For black leaders and community organizers, National Negro Health Week campaigns provided a way to advance the race through the promotion of black health education and cooperation across racial lines.

The program expanded throughout the country, and by the early 1930s, an average of thirty-two states held health campaigns each year. In 1932, the U.S. Public Health Service opened the Office of Negro Health Work, which became the headquarters for the National Negro Health Movement, a year-round effort to improve African American health.

Shortly after Elizabeth Porter arrived in Frederick, Meg ended her tenure at the Frederick County Public Health Association, returning to the Henry Street Settlement House, but the fact that years later, she specifically mentioned Ms. Porter's placement in Frederick County on her resume is evidence that she was proud of this accomplishment--and that she considered it a story that should be remembered.

**Further Reading**:

Smith, Susan L. *Studies in Health, Illness, and Caregiving: Sick and Tired of Being Sick and Tired: Black Women's Health Activism in America, 1890-1950*. Philadelphia: University of Pennsylvania Press, 2010.
