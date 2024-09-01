;
;	>>> Call Now !!! - actual size edition<<<
;
;	(c) 2015-02-16 by JAC!
;
;	My 4 minutes contribution to https://www.pouet.net/search.php?what=call+now&type=prod.
;
;	Properly centered in middle of the screen.
;	Correct number of exclamation marks.
;	Extra epileptic flashing mode that also turns characters upside down sometimes.
;	30 bytes including 6 bytes executable header.

	org $600
	asl $bc24
	sec
loop	rol $2f3
	bvc loop

	org $bc40+40*11-2
	.by +$60 "CALL NOW!!!"
