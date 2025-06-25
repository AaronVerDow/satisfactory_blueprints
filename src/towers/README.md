# Towers

Production towers for parts. The goal of these towers is to produce simple items in bulk (ingots, concrete, plastic/rubber) and only distribute those parts. Everything else is made as needed inside the blueprint, simplifying factories and their dependencies.

The towers adhere to the following rules:

* I/O is on one face for easy connection to a bus.
* I/O passes through to opposite face for horizontal connections.
  * These are not designed for auto connect.
* I/O passes through top so units are stackable.
* Inputs start on the right, outputs are on the left. (There are some exceptions.)
* Only use simple inputs. These can be produced en masse using pure and wet recipes.
  * Ingots
  * Concrete
  * Plastic/Rubber
* Production speeds of all machines are balanced.
* Use the slowest conveyors possible.
  * This helps balance distribution, and I think it looks cooler.
* Color code everything by part.
  * This may not be consistent between blueprints, it only helps to trace conveyors easier.
* Label I/O totals.
* No efforts have been made to conserve resources.
