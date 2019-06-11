---
# Manufacturer Metadata
title: "{{ replace .Name "-" " " | title }}" # Display name for the manufacturer
date: {{ .Date }} # Date when this entry was first created
lastmod: {{ .Date }} # Date this entry was last modified
summary: They make synths # One-sentence description of the company
draft: true # `true` if the entry shouldn't be published yet
sameAs: # https://schema.org/sameAs

# Organization Details
foundingDate:   # https://schema.org/foundingDate
founder:    # https://schema.org/founder
foundingLocation:   # https://schema.org/foundingLocation
location:   # https://schema.org/location
---

_Thoughtful description..._

