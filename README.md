# DisneyTVA Programs
A summary of all programs aired by Disney Television Animation.<br><br>
*Last Updated: December 12, 2023*

## About Disney TVA
**Disney Television Animation** (est. December 5, 1984) is an animation studio that serves as the TV animation production unit of Disney Branded Television, a division of Walt Disney Television. The division is responsible for creating, developing and producing animated television series, films, specials and short films.

The company has produced shows for several major networks such as ABC and CBS. They have also produced shows for syndication blocks, including The Disney Afternoon and One Saturday Morning. Today, Disney TVA primarily manages content on the three main Disney-branded networks; **Disney Channel**, **Disney XD** and **Disney Junior**, as well as the **Disney+** steaming service.

## Variables

**95** programs that have been or are currently broadcast on Disney TVA programming. This dataset will be updated occasionally as new shows make their premieres.

**16** variables about each show.

| Variable      | Description |
| -----------   | ----------- |
| number        | ID. Shows are ordered by Premiere Date. |
| title         | Name of the show. |
| creator       | Main creator(s) or developer(s) of the show. Does not include producers or directors. |
| seasons       | Number of seasons. |
| episodes      | Number of episodes (segments) aired. |
| primaryTime   | Typical length of an episode of the show, in minutes (see Notes). |
| premiereDate  | Air date of the show's first episode. In YYYY-MM-DD format. |
| finaleDate    | Air date of the show's last episode. "2024-12-31" if show is currently airing. In YYYY-MM-DD format. |
| DC            | Disney Channel (1983-Present) |
| Synd          | Syndication Blocks: The Disney Afternoon (1990-1997), One Saturday Morning (1997-2002), ABC Kids (2002-2011), One Too (1999-2003) |
| ABC           | Aired shows as part of syndication blocks |
| CBS/UPN       | Aired shows as part of syndication blocks; UPN was owned by CBS and replaced with The CW in 2006 |
| Toon          | Toon Disney (1998-2009); includes Jetix block; replaced by Disney XD |
| XD            | Disney XD (2009-Present) |
| Junior        | Disney Junior (2011-Present); includes Playhouse Disney (1999-2011) |
| D+            | Disney+ streaming service (2019-Present) |

#### Notes
- primaryTime: Describes the length (in minutes) of a *majority* of the show's episodes. Many shows have mostly 11- or 22-minute episodes.
  - Shows with a value of **5** have episodes much shorter than 11 minutes. These are usually shows consisting of primarily shorts (5 minutes or less).

- The last 8 variables (DC to D+) refer to 7 different TV networks and 1 streaming service. For a given show, the value of a network variable is **1** if the channel *regularly aired new episodes* at any point during the show's run, and **0** otherwise. Reruns are not included.
  
- Episode count does not include feature films or additional shorts, unless the program consists of primarily shorts.

- *Doug* aired a total of 166 episodes for seven seasons. The first four seasons aired on Nickelodeon, and the last three on ABC. This database only records the last three seasons (65 episodes) that aired during the show's run under Disney TVA.

## Contributing

If you believe there is inaccurate or misleading data, please leave a comment, and I'll make sure to write back!

Read some of my analysis on these shows in my [Observable notebook](https://observablehq.com/@eugenerbl/disney-tva-programs).

## License

[MIT](https://choosealicense.com/licenses/mit/)
