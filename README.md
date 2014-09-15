fourteen_segments
=================

Pin mapping of ASCII characters to a 14-segments display through 14 digital IO's. 
This was used in a project where we built a GIANT 14-segment display (6 meters high).

The pin mapping is done with arrays. Following array of chars corresponds to the segments of the 14-segments below:

char ASCIICharacter[] ={1,2,3,4,5,6,7,8,9,10,11,12,13,14};

e.g. char zero[] ={1,1,1,1,1,1,0,0,0,0,1,0,0,1};

                                1
                ,CCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCC:        
            ,CCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCC,      
        .C; fLCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCf iC.  
      .CCCCC; fCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCf.;CCCCC.
      CCCCCCC:  .                                 :LCCCCCC
      CCCCCCC: CCf          CCCCCCCC          fCL :LCCCCCC
      CCCCCCC: LCCf  9      CCCCCCCL 10     fCCL :LCCCCCC
      CCCCCCC: CCCCf.       CCCCCCCL        fCCCC :LCCCCCC
      CCCCCCC:  CLCCf       CCCCCCCL       fCCCC  :CCCCCCC
      CCCCCCC:   CCCCt      CCCCCCCL      tCCCC   :CCCCCCC
    6 CCCCCCC:    LCCCf     CCCCCCCL    .fCCCL    ;CCCCCCC 2
      CCCCCCC:     tCCCt    CCCCCCCL    tCCCt     :CCCCCCC
      CCCCCCC:      1CCCf   CCCCCCCC  .fCCC1  11  :CCCCCCC
      CCCCCCC:       ;LCCt  CCCCCCCL..tCCL;.      :CCCCCCC
      CCCCCCC:        :CCC: CCCCCCCC :CCL,        :CCCCCCC
      CCCCCCC:         ,LL: CCCCCCCL :CC,         :LCCCCCC
      CCCCCCC:      7       .CCCCCC.      8      :CCCCCCC
      ,CCCCCf iCCCCCCCCCCCC.  .CC.  .CCCCCCCCCCt . tCCCCC;
        ,Lt iLCCCCCCCCCCCCCCC,    .CCCCCCCCCCCCCCt  .tC:  
       ,Cf iLCCCCCCCCCCCCCCC. CC..CCCCCCCCCCCCCCt  .fC:. 
      ,CCCCCf.iLCCCCCCCCCCC,.CCCCCC .CCCCCCCCCCt   fCCCCC;
      CCCCCCC:              CCCCCCCC              :CCCCCCC
      CCCCCCC:         .CC: CCCCCCCC :CC.         :CCCCCCC
      CCCCCCC:        ,LCC:.CCCCCCCC :CCC,        :CCCCCCC
      CCCCCCC:       ;CCLt  CCCCCCCC  fCCL; 12    :CCCCCCC
      CCCCCCC:      1CCCt   CCCCCCCC   fCCCi      :CCCCCCC
      CCCCCCC:    .tCCCt    CCCCCCCL    fCCCf     :CCCCCCC 3
    5 CCCCCCC:    LCCCf     CCCCCCCL     fCCCL    :CCCCCCC
      CCCCCCC:   CCCCf      CCCCCCCL      fCCCC   :CCCCCCC
      CCCCCCC:  CLCCf 14   CCCCCCCL       fCCCC  :CCCCCCC
      CCCCCCC: CCCCf        CCCCCCCL 13    fCCCC :CCCCCCC
      CCCCCCC: LCCf         CCCCCCCL         fCCL :CCCCCCC
      CCCCCCC: CCf          CCCCCCCL          fCC :CCCCCCC
      CCCCCCC:                                  . ;CCCCCCC
      .CCCCC;.LCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCf ;CCCCC.
       .C; fCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCf ;G.  
           ,CCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCC,      
              ,CCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCL,        
                               4
