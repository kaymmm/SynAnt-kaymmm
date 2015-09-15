# SynAnt-kaymmm
big huge thesaurus alfred workflow fork

This is a custom fork of [this workflow](http://www.packal.org/workflow/synant).

To use the workflow, you need to get an api key from the [BigHugeThesaurus website](https://words.bighugelabs.com/getkey.php).

## Usage

[trigger alfred] -> `[command] [word] [pos]`
[highlight selection, hit keycombo] -> `[command and word piped in] [pos, optional]

`command` is one of `syn` (synonym), `ant` (antonym), `rel` (related words), or `thes` (all results, see `pos` below for more)

`pos` is one of `n/v/a/av`

* `n`=noun
* `v`=verb
* `a`=adjective
* `av`=adverb

`thes` returns all results, but you can filter by the pos value, which can be
 
* `n/v/a/av` or `r/s/syn/rel/ant/sim` or any other term
* `r`=related words
* `s`=similar words
* `syn`=synonyms
* `rel`=related words
* `ant`=antonyms
* `sim`=similar words
* anything else you type will be the filter term for results (e.g., "re" to filter by words starting with the prefix "re")
