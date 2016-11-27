When and what is the GPS week rollover problem? (FAQ - Time)
GPS, the Global Positioning System, has its own date and time scale for expressing satellite positions, based on counting weeks, and seconds within a week. To limit the size of the numbers used in the data and calculations the GPS Week Number is a ten-bit count in the range 0-1023, repeating every 1024 weeks. Week 0 started at 00:00:00 UTC on Sunday, 6th January 1980, so the week number 'rolled over' from 1023 to 0 at 23:59:47 UTC on Saturday, 21st August 1999. This was before midnight UTC because every GPS week contains exactly 604 800 s, to keep the calculations consistent. The 13 intervening leap seconds had put UTC behind GPS system time.

The problem is that some GPS-based equipment or software may be confused by the rollover event, which is similar to the year-2000 software problems. Anyone likely to be affected should seek advice from the manufacturer or supplier of the product concerned. The GPS week rollover next occurs on 2019 April 06.

Last Updated: 25 Mar 2010
Created: 9 Aug 2007
