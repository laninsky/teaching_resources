|  **Sample ID**  |         **Species ID from BLAST**                 |
|  J08-021B       | *Balaenoptera physalus* (fin whale)               |
|   J01-007       | *Balaenoptera bonaerensis* (Antarctic minke)      | 
|   J01-008       | *Berardius bairdii* (Baird's beaked whale)        | 
|   J09-011       | *Balaenoptera acutorostrata* (common minke whale) | 
|   J09-029       | *Megaptera novaeangliae* (humpback whale)         | 

### Advantages and disadvantages of this approach
One advantage of BLAST is that the database is updated frequently, so it has lots of sequences for each species. However, one of the downsides of BLAST is that these sequences are not expertly curated. If sequences have been uploaded with the wrong species identification, we could be misled if they match to our sequence of interest. Also, with BLAST it isn't super easy to "peak" below the species level to identify geographic locations samples are from. This is something you might be able to do if you instead had a 'curated database'

## When can there be issues using mtDNA to identify species?
- DNA sequence too short: if the sequences used with either method are too short, we might not capture enough of the unique mutations that allow us to tell species apart
- Sometimes even with full-length sequences species cannot be distinguished. This isn't such a problem with the control region, but other parts of the mtDNA can be identical between different species
- When you have a new species! BLAST will still give you a match, but it might have a lower % of identity. It can be difficult to decide how different a sample has to be from other species to consider that it might be a new species!
