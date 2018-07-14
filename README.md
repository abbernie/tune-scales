# TuneJS Scales

**Authors:** Andrew Bernstein & Ben Taylor

**Overview:** Tune.js is a web audio tuning library of microtonal and just intonation scales. Tune.js supports over 3,000 historical tunings and temperaments, ported from the vast [Scala](http://www.huygens-fokker.org/scala/) tuning archive via the Microtuner files [compiled and documented by Victor Cerullo](http://www.venetica.net/Sites/16tone/mtx_file_specs.htm).

This specific repo contains all the tunings in Tune.js, both as a single file (tunings.js) and as individual JSON files that can be imported selectively. These tunings are designed to be used with the [standalone Tune.js API](https://github.com/abbernie/tune-api), which doesn't include any tunings by default.

By separating these into two separate repos you can choose exactly what tunings you want to import, and where the tunings are located on your server, independently of the location of the API. However, the easiest way to use Tune.js is to just download a single file that contains both the API and all the tunings; you can do this using the [main tune.js repo](https://github.com/abbernie/tune).

**List of Tunings:** [Tuning Archive](http://abbernie.github.io/tune/scales.html)

**Demo:** [Microtonal Piano](http://abbernie.github.io/tune/)

### Example Tunings

| Name | Description |
|------|-------------|
| ji_12 | Basic just instonation with 7-limit tritone |
| harm30 | First 30 harmonics and subharmonics |
| pyth_31 | 31-tone Pythagorean scale |
| ptolemy | Intense Diatonic Syntonon, also Zarlino's scale |
| couperin | Couperin modified meantone |
| helmholtz_pure | Helmholtz's two-keyboard harmonium tuning untempered |
| partch_43 | Harry Partch's 43-tone pure scale |
| johnston_81 | Ben Johnston's 81-note 5-limit scale of Sonata for Microtonal Piano |
| young-lm_piano | LaMonte Young's Well-Tempered Piano |
| xenakis_chrom | Xenakis's Byzantine Liturgical mode, 5 + 19 + 6 parts |
| slendro | Observed Javanese Slendro scale, Helmholtz/Ellis p. 518, nr.94 |
| harrison_5 | From Lou Harrison, a pelog style pentatonic |
| malkauns | Mode of Indian Raga Malkauns, inverse of prime_5 |

![BigP](http://www.mathopenref.com/images/bioimages/pythagoras1.jpg)
![BigZ](https://upload.wikimedia.org/wikipedia/commons/thumb/2/22/Gioseffo_Zarlino.jpg/200px-Gioseffo_Zarlino.jpg)
![Partch](http://www.pas.org/images/default-source/hall-of-fame-photos/hpartch.jpg?sfvrsn=0)

### License

Tune.js is licensed as open source software under [the MIT license](https://opensource.org/licenses/MIT), 
Archive copyright 2003-2010 by Victor Cerullo

