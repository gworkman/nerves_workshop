# Nerves Workshop - Berlin BEAM Week 2025

This repo contains all the resources used in the Nerves Workshop for Berlin BEAM
Week 2025. The event details can be found
[here](https://www.meetup.com/elixir-berlin/events/311640395).

In this workshop, we'll be using and talking about
[Project Soleil](https://protolux.io/projects/soleil)

## Getting Started

We will be using Nerves Livebook for this event. There is a new tool to quickly
flash Nerves images on the officially supported Nerves systems, called
`Nerves Burner`. Please go to
[the repo](https://github.com/nerves-project/nerves_burner) and follow the
instructions. Note that you need to install the `fwup` utility first. If you are
on Mac, simply `brew install fwup`. Linux and Windows, please see the install
instructions.

Specifically, for this workshop we want to use the Nerves Livebook image, and to
prevent us from overloading the WiFi network, we will **not** set up WiFi
credentials.

If you need help flashing for any reason, or you need a USB-C to micro SD
converter, please come see me.

## Details

The rest of this document will be filled out after the event!

## Resources

- [MCP7940N datasheet](https://ww1.microchip.com/downloads/aemDocuments/documents/MPD/ProductDocuments/DataSheets/MCP7940N-Battery-Backed-I2C-RTCC-with-SRAM-20005010J.pdf)
- [NervesTime docs](https://hexdocs.pm/nerves_time/readme.html)
- [NervesTime.RealTimeClock example implementation](https://github.com/nerves-time/nerves_time_rtc_ds3231)
- [Soleil elixir library](https://hexdocs.pm/soleil/introduction.html)
- [Soleil hardware repo](https://github.com/protolux-electronics/soleil_hardware)
- [Soleil hardware design overview blog post](https://protolux.io/blog/soleil-hardware-design)
- [Soleil system for RPi Zero 2W](https://github.com/protolux-electronics/soleil_system_rpi0_2)
