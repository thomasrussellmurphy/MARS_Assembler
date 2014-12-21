## MARS Assembler
[MARS][1] is a lightweight interactive development environment (IDE) for programming in MIPS assembly language, intended for educational-level use with Patterson and Hennessy's Computer Organization and Design.

MARS has been jointly developed by [Pete Sanderson][4] (programming) and [Ken Vollmar][5] (details and paperwork).

## Download
You can download the latest version [at the official website][6].

## Purpose of this repo
This repo is a mirror of the source code of MARS Assembler. Though the source code is into the "MARS.jar" file at the download page, this is a mirror for people who wants to have the source code forked or that stuff.

I'm not going to accept any pull request. This source code is not maintained by me but the original developers. If you want to contribute to the project, you should talk with them [going here][8].

## Documentation (included in the repo)
 - Go to the [documentation][7].
 - In order to run or compile MARS v4.XX, **MARS requires Java J2SE 1.5 (or later) SDK installed on your computer**.

## How to run MARS
 - **Option A**: Desktop. Save the jar file on the desktop. Run MARS by double-clicking the icon.
 - **Option B**: DOS shell using jar file. Save the jar file in some folder. Open a DOS shell in that folder. Rename the jar file to "Mars.jar" for convenience. Run MARS with the DOS command  java -jar Mars.jar
 - **Option C**: DOS shell using Java classes. Save the jar file in some folder. Open a DOS shell in that folder. Rename the jar file to "Mars.jar" for convenience. Extract MARS files with the DOS command  jar -xf Mars.jar Run MARS with the DOS command  java Mars

## How to compile
 - **Windows**: execute "CreateMarsJar.bat" file to generate an executable.
 - **GNU/Linux** and **Mac**: execute the "CreateMarsJar.sh" to generate an executable. If you can't due of permissions, do a "**chmod +x CreateMarsJar.sh**" (Thanks to [@aesptux][8] to be the tester in Mac).

## License
[MIT][2]. Chech the [LICENSE][3] file. All the credits go to the original developers.

  [1]: http://courses.missouristate.edu/KenVollmar/MARS/index.htm
  [2]: http://www.opensource.org/licenses/mit-license.html
  [3]: https://github.com/adolphenom/MARS_Assembler/blob/master/LICENSE
  [4]: http://faculty.otterbein.edu/PSanderson/
  [5]: http://courses.missouristate.edu/KenVollmar/
  [6]: http://courses.missouristate.edu/KenVollmar/MARS/download.htm
  [7]: http://courses.missouristate.edu/KenVollmar/MARS/Help/MarsHelpIntro.html
  [8]: http://twitter.com/aesptux