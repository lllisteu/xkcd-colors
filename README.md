[GitHub](https://github.com/lllisteu/xkcd-colors) 

# xkcd Color Name Survey

A palette of 954 named colors from the [xkcd](https://xkcd.com/) color name survey, in GPL format.

## Background

In March 2010 Randall Munroe announced a color name survey, asking visitors to name colors.

* [Color Name Survey](https://blog.xkcd.com/2010/03/01/color-name-survey/) (1 March 2010)

In total, "over five million colors were named across 222,500 user sessions". The resulting list of the 954 most common named colors was published in May 2010. 

* [Color Survey Results](https://blog.xkcd.com/2010/05/03/color-survey-results/) (3 May 2010)

A cleanup then removed 5 colors ("survey artifacts"), and the remaining 949 named colors were published as a text file.

* [rgb.txt](https://xkcd.com/color/rgb.txt)

## Files

Published here are three files in GPL format (Gimp color palette):

* [xkcd_954.gpl](xkcd_954.gpl)
  All 954 colors, extracted from [https://xkcd.com/color/rgb/](https://xkcd.com/color/rgb/).
  
* [xkcd_949.gpl](xkcd_949.gpl)
  949 colors, converted from [https://xkcd.com/color/rgb.txt](https://xkcd.com/color/rgb.txt) and sorted in reverse order.
  
* [xkcd_5.gpl](xkcd_5.gpl)
  The 5 colors ("survey artifacts") removed from the 954-color set to obtain the 949-color set.

## Credits

Thank you to Randall Munroe and relsqui for creating the xkcd color survey, and publishing the results.

## Tools

[Ruby](https://www.ruby-lang.org/) and [redgreenblue](https://rubygems.org/gems/redgreenblue).

## License

This dataset is placed in the public domain using a [CC0 License](LICENSE.txt).
