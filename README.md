# IOF Data Standard, version 2.0.3

> ⚠️ **WARNING:** this is an outdated version of the data standard. [Find here](https://github.com/international-orienteering-federation/datastandard-v3) the latest version

This is the first standard that will be widely implemented by software developers including the two EKT system, Emit and Sport Ident.

The standard is a total rewrite as a result of the experiences gained in the Swedish OLA Project and the development of Condes. Also major input have been made by Emit and Sport Ident developers.

The changes from version 1.0 includes:

* A total rewrite of nearly all elements.
* Instead of having several Document Type Declaration (DTD) files each holding a small part of the standard and depending on each other the DTD is now assembled in a single file.
* A number of messages, i.e. specification of the lists to be send from one software element to another, have been made. There still are some messages missing and they will be developed concurrently with demand for them.
* Some example files of the messages to exchange have been made.
Please read the comments in the DTD file for further information.

[IOF Data Standard 2.0.3 DTD](IOFdata.dtd)

  The file is organized in a number of sections:
  - Person
  - Competitor
  - Club
  - Event
  - Entries
  - Start List
  - Result List
  - Classes
  - Controls and Courses
  - "Office" elements, i.e. non-orienteering and generic
  
  In the top of each section is a reference to the name of the
  lists that are meant to be exchanged between different software
  packages used in an orienteering event.
  A quick reference to these lists are:
  - PersonList - rarely used
  - CompetitorList - "brutto" list, e.g. a national database
  - RankList - competitors in a ranking list, e.g. World Ranking
  - ClubList - club database, national or event specific
  - EventList - used for fixtures
  - ServiceRequestList - rarely used
  - EntryList - club ordered entries for an event
  - StartList - class ordered start list
  - ResultList - class ordered results, not necessarily complete
  - ClassData - list of classes, national or event specific
  - CourseData - list of controls and courses of an event
  
  ### Authors:
 * Stefan Nordmark, SWE
 * Kell Sønnichsen, DEN
 * Finn Arildsen, DEN
  
  Date: 01-2002