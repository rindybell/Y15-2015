# Multiword Expression (MWE) annotations on OntoNotes
We provide users with MWE annnotations on OntoNotes - 938,688 tokens (include a linefeed), which is based on the following paper: An Efficient Annotation for Phrasal Verbs using Dependency Information [1].

We provide MWE annotations with two type formats:

   1. Head Style Format	   (resource/wsj_ontonotes_head.conll)
   2. BIO Format	   (resource/wsj_ontonotes_bio.conll)

## Head Format

MWE information is represented as one column in Head Style Format. <br>
The column consists of POS, position, or underscore (_).

- A POS indicates the head token of an MWE, and means a appropriate POS of the MWE.

- A position indicates the tail tokens of an MWE, and means a position of the head of it.

- An underscore (_) indicates a token except for an MWE.

Example: 

	24	that	_
	25	show	VB
	26	up	25

## BIO Format

This format is same as **Gappy, 1-level (6 tags)** in [2]. <br>
Please see also [2].

## References
- [1] Masayuki Komai et al. 2015: An Efficient Annotation for Phrasal Verbs using Dependency Information. 29th Pacific Asia Conference on Language, Information and Computation, pages 125-131
- [2] Nathan Schneider et al. 2014a: Discriminative lexical semantic
segmentation with gaps: Running the MWE gamut. Transactions of the Association of Computational Linguistics (TACL) – Volume 2, Issue 1, pages 193–206.

## E-Mail

komai.masayuki.jy4 /at/ is.naist.jp

## Contributors
- Masayuki Komai
- Hiroyuki Shindo
- Yuji Matsumoto