# colors.h (Library)
Bring colors to your C terminal/console project

## Usage
If you want paint your text of < COLOR >, write:
> c_< COLOR >();

Where <COLOR> is one of the available colors, for example:
> c_red();
  
> printf("This text is red.\n");

> c_cyan();

> printf("Goodbye!"); // This text prints in cyan's color

## Available colors
- c_reset() 
- c_red()
- c_boldRed()
- c_green()
- c_boldGreen()
- c_yellow()
- c_boldYellow()
- c_blue()
- c_boldBlue()
- c_magenta()
- c_boldMagenta()
- c_cyan()
- c_boldCyan()
- c_silver()
- c_boldSilver()
- c_darkBlue()
- c_boldDarkBlue()

## Note
cyan and boldCyan outputs yellow IN SOME Linux terminals...
If that happens to you, note yellow and boldYellow are darker than normal.
darkBlue and darkBlueBold only work in Linux, sorry for the inconvenience. */
