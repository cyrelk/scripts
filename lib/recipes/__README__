All scripts stored into this folder are 'recipes'. A recipe is
a small action involving the creation and or modification of
the state of a node (a Physical Machine) or a domain (a Virtual
Machine or a Container).

Recipes can be run standalone but their purpose is to be run by
the 'runner' script. This script will read information stored
in a database and will launch each recipe for each instruction
stored. It's up to the recipe to read all the necessary information
from the database or some configuration file to complete its task.
In the future it should be possible that recipes been used as
services that listen on a socket and respond to events sent
using 0MQ or some AMQP mechanism, this is debatable.

Recipes can be coded in any language, but for the sake of
Mezzapp, Bash, Python and Javascript will be the main languages
used.
