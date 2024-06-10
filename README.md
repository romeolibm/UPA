# UPA
Universal Parser Architecture

## Requirements

1. A UP (Universal Parser) is a parser that reads any data structure (file, stream, object etc) and produces a list of metadata entities describing the structure (componnts) of the input object relative to a GUT/LUT taxonomy
2. Subsequent parsers of any object in parsed layer will simply be a reccurent parser associated to each object structure (discovered) and this process applies until the object in the parset list is a leaf/atomic object (an object that can't be further parsed such as a number, id, character etc.

## Related repositories
 * [GUT-Requirements](https://github.com/romeolibm/GUT-Requirements/blob/main/README.md)
 * ...
