# Sistem-SDR-pentru-testarea-unui-Modem-TT-C
Acest repository conține lucrarea mea de disertație, realizată în cadrul programului de masterat Sisteme electronice și de comunicaţii integrate-RCD, la Univ. Transilvania din Brașov. Prin acest sistem am dezvoltat un sistem SDR în MATLAB, destinat generării, prelucrării și transmiterii semnalelor specifice comunicațiilor satelitare TT&C.

În Figura 1 este reprezentată arhitectura generală a sistemului propus. Un calculator care rulează MATLAB generează datele utile (CADU/CLTU), aplică scheme de codare pentru corecția erorilor (Reed-Solomon/BCH) și adaugă markere de sincronizare. În continuare, în MATLAB, datele sunt modulate BPSK și filtrate RRC, iar eșantioanele I/Q rezultate sunt trimise către hardware-ul SDR pentru transmisia radio.
<img width="2001" height="483" alt="image" src="https://github.com/user-attachments/assets/67f81877-820e-4941-9f6d-bd556ab7807a" />
                                Figura 1. Arhitectura sistemului
