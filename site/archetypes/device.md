---
# Device Metadata
title: "{{ replace .Name "-" " " | title }}" # Display name for the device (without manufacturer)
date: {{ .Date }} # Date when this entry was first created
lastmod: {{ .Date }} # Date this entry was last modified
summary: It's a synth # One-sentence description of the device
draft: true # `true` if the entry shouldn't be published yet
sameAs: # https://schema.org/sameAs

# Manufacture Details
manufacturer: Company # Taxonomy, https://schema.org/manufacturer The name of the company that manufactured this device
availability: InStock # https://schema.org/availability one of ["Discontinued", "LimitedAvailability", "InStock", "PreOrder"]
brand: Brand # Taxonomy, https://schema.org/Brand

# Physical Details
dimensions:
  width: 100 # Distance from the left to the right of the device in millimeters
  depth: 100 # Distance from the front to the back of the device in millimeters
  height: 100 # Distance from the top to the bottom of the device in millimeters
  weight: 10 # The mass of the device in kilograms

# Purchase options
offers: # https://schema.org/offers
  - seller: # https://schema.org/seller
    price: # https://schema.org/price
    priceCurrency: # https://schema.org/priceCurrency
    url: # https://schema.org/url
---

_Thoughtful description..._

