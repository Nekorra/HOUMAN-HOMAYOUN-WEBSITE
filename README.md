# Installation
If using homebrew, run:
    brew install hugo

if using MacPorts, run:
    port install hugo

else:
    download latest binary release from https://github.com/gohugoio/hugo/releases
    and then add hugo to your system path for ease of use

# Seeing your changes
In your shell, run 'hugo server' to see any changes that you make in your website

# I want to...

## Add funding

1. copy: 
    {
        "timespan": "",
        "amount": "",
        "source": "",
        "purpose": "",
        "role": ""
    },

2. Paste as first element in '/data/funding.json' and fill in fields.

## Add an honor

1. copy:
    {
        "name": "",
        "url": "",
        "earnings": "",
        "extra": "",
        "timespan": ""
    },

    The key "extra" refers to any other information you want to include about the honor.
2. Paste as first element in '/data/honors.json' and fill in fields.

## Add New Event

1. copy:
    {
        "month": "",
        "details": ""
    },

2. Paste as first element in the events list in the target year in '/data/events.json'.

## Add a New Interest

1. Add interest string in '/data/interests.json'

## Add a New Journal

1. copy:
    {
        "journal": "",
        "title": "",
        "file_name": "",

        "authors": "",
        "details": ""
    },

2. Add to list in '/data/journals.json'

## Add a New Conference

1. copy:
    {
        "journal": "",
        "title": "",
        "file_name": "",
        "authors": "",
        "details": ""
    },

2. Add to list in the appropriate year in '/data/conferences.json'

## Add a New Research

1. copy:
    {
        "title": "",
        "content": "",
        "img_name": ""
    },

2. Add to list in '/data/research.json'

## Add a New Sponsor

1. Add image file to '/static/images/sponsors'

## Add New Personnel

For phd's or master's copy and add to '/data/people.json':
    {
        "name": "",
        "research": "",
        "img_name": ""
    },


For undergraduates add name to undergraduates list in '/data/people.json'


For post doc alumni copy and add to '/data/people.json':
    {
        "name": "",
        "job": "",
        "img_name": ""
    },

For phd alumni and master's alumni copy and add to '/data/people.json':
    {
        "name": "",
        "thesis": "",
        "job": "",
        "img_name": ""
    },

For undergraduate alumni add name to undergraduates list in '/data/people.json'

## Add a new class

1. Add text for new class in 'data/teaching.json'

## Add a service

1. Add service to 'data/service.json'

## Change the announcement for positions

1. Change the message in 'data/announcement.json'

# Wrapping up
In your shell, run 'hugo' to compile your website. You can now upload the 'public' directory to your server.