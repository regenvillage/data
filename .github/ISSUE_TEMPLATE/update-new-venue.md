---
name: Update/New Venue
about: Ask us to update or add a new event location to the Regen Village website
title: "[NEW]: "
labels: new
assignees: ""
---

Please use this template to suggest a new event location or update an existing one for the Regen Village website! You can also directly [submit your event as a pull request](https://github.com/regenvillage/data/tree/main/data/24/places) to this repository. This will speed up things significantly!

```toml
# name of the venue
name = "Example Venue"

# type of the event
#  available types (you can choose more):
#   * meetup
#   * conference
#   * hackathon
#   * expo
#   * party
#   * other
eventTypes = ["conference", "hackathon"]

# max number of attendees
capacity = 350

# Street address
address = "Cantersteen 12, 1000 Bruxelles"

# OSM Maps URL
mapUrl = "https://nominatim.openstreetmap.org/ui/search.html?q=becentral"

# Venue Description
description = '''
BeCentral is the digital campus located in Brussels Central Station. Cofounded and backed by more than 60 entrepreneurs, we are a place to learn technologies, grow a startup and impact society. Our mission is to make everyone an actor of the digital revolution.
'''

# Venue Photo or Logo
photo = "logo.png"

# Venue Link
[links]
web = "https://example.com/spaces/"
```
