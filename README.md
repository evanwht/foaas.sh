# foaas.sh - Command Line Fuck Off as a Service client

foaas.sh is a command line [Fuck Off as a Service client](http://foaas.com/). It is written is bash and supports multiple forms of API interaction. It also supports `xclip`, when available, the result of an interaction is copied to the clipboard for later use.

## Usage

    $ ./foaas.sh help

    foaas.sh - command line Fuck Off as a Service client ()
    Usage:
    ./foaas.sh [name|/:from endpoint]

    ./foaas.sh [name] [from]
    ./foaas.sh [/:name/:from endpoint] [name]

    ./foaas.sh [/:name/:from endpoint] [name] [from]

    Endpoint is random by default.
    All arguments are optional, unix username is used by default. 
    When xclip is installed, the result will also be on your clipboard.

    /:from endpoints: this that everything everyone pink life thanks flying fascinating
    /:name/:from endpoints: off you donut shakespeare linus king chainsaw madison


## Alias Fuck

Add this to your bashrc:

    alias fuck="/path/to/foaas.sh"

Start a new shell and type `fuck` or for example, `fuck Joe`.


## Examples

    $ fuck                   
    http://foaas.com/everyone/Remy
    Everyone can go and fuck off. - Remy


    $ fuck Name
    http://foaas.com/donut/Name/Remy
    Name, go and take a flying fuck at a rolling donut. - Remy


    $ fuck Name From
    http://foaas.com/chainsaw/Name/From
    Fuck me gently with a chainsaw, Name. Do I look like Mother Teresa? - From


    $ fuck madison Name
    http://foaas.com/madison/Name/Remy
    What you've just said is one of the most insanely idiotic things I have ever heard, Name. At no point in your rambling, incoherent response were you even close to anything that could be considered a rational thought. Everyone in this room is now dumber for having listened to it. I award you no points Name, and may God have mercy on your soul. - Remy

## License

    # Author: Remy van Elst, https://raymii.org
    # 
    # This program is free software; you can redistribute it and/or modify it 
    # under the terms of the GNU General Public License as published by the 
    # Free Software Foundation; either version 2 of the License, or (at your 
    # option) any later version.
    # 
    # This program is distributed in the hope that it will be useful, but 
    # WITHOUT ANY WARRANTY; without even the implied warranty of 
    # MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU 
    # General Public License for more details.
    # 
    # You should have received a copy of the GNU General Public License along 
    # with this program; if not, write to the Free Software Foundation, Inc., 
    # 51 Franklin Street, Fifth Floor, Boston, MA  02110-1301, USA.
    # 