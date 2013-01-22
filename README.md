Copyright (c) 2013, Phil Gooch. 
This software is licenced under the [GNU Library General Public License](http://www.gnu.org/copyleft/gpl.html) Version 3, 29 June 2007.

See LICENSE.txt file for license details.

* * * *


Biomedical Predicate VerbGroup Chunker (BioPred)
================================================

This plugin extends the ANNIE VP Chunker[1] to provide chunking of complete predicate verb groups, including identification of negated modals, for identifying relations in biomedical text.


[1]: H. Cunningham, D. Maynard, K. Bontcheva, V. Tablan. GATE: A Framework and Graphical Development Environment for Robust NLP Tools and Applications. Proceedings of the 40th Anniversary Meeting of the Association for Computational Linguistics (ACL'02). Philadelphia, July 2002.


How to use this plugin
=======================

BioPred is compatible with [GATE version 7.1](http://www.gate.ac.uk/) and higher. Simply create an instance of the JAPE or JAPE Plus Transducer, and point it to the _main.jape_ file in this folder.

Be sure to add a Tokenizer, Sentence Splitter and POS Tagger to your pipeline before running this plugin.
