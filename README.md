# fluent-fisher


This dataset contains fluent English reference translations re-written with disfluencies removed for the LDC Fisher Spanish dataset. 
They were collected via Mechanical Turk using the original disfluent translations. 
It complements the original LDC Fisher audio and transcripts, and translations collected by [JHU](https://joshua.incubator.apache.org/data/fisher-callhome-corpus/), creating a parallel disfluent/fluent corpus to promote further research in producing fluent output from disfluent data. 

The `ids/` directory contains the data with prepended utterance ids and files containing the id lists. 

The `noids/` directory contains the text only. 

The utterances ids and mappings correspond to those created for the original English translations. 
The submodule [fisher-mapping](https://github.com/esalesky/fisher-mapping.git) maps Fisher speech features to match these translation ids.
Please see [here](https://github.com/joshua-decoder/fisher-callhome-corpus) for more information. 


For a complete description of this corpus, please refer to the following paper.
If you use this corpus, please cite in your work:

    @inproceedings{salesky2018slt,
      Title = {Towards Fluent Translations from Disfluent Speech},
      Author = {Salesky, Elizabeth and Burger, Susanne and Niehues, Jan and Waibel, Alex},
      Booktitle = {Proceedings of the IEEE Workshop on Spoken Language Technology (SLT)},
      Year = {2018},
      Address = {Athens, Greece},
      Month = {December}
    }

Initial results translating from disfluent source speech to this fluent data are described here:

    @inproceedings{salesky2019naacl,
      Title = {Towards Fluent Translations from Disfluent Speech},
      Author = {Salesky, Elizabeth and Sperber, Matthias and Waibel, Alex},
      Booktitle = {Proceedings of the North American Chapter for the Association of Computational Linguistics(NAACL)},
      Year = {2019},
      Address = {Minneapolis, USA}
      Month = {June}
    }
