## Alfred Workflow for StarDict CLI (sdcv)

### setup

- Run `brew install sdcv jq`
- Download dictionaries files:
    * [langdao-ec](https://raw.githubusercontent.com/ruoshan/stardict-alfredworkflow/master/stardict-langdao-ec-gb-2.4.2.tar.bz2)
    * [langdao-ce](https://raw.githubusercontent.com/ruoshan/stardict-alfredworkflow/master/stardict-langdao-ce-gb-2.4.2.tar.bz2)
- Extract and place to the right place
    * `mkdir -p ~/.stardict/dic`
    * `tar jxf stardict-langdao-ec-gb-2.4.2.tar.bz2 -C ~/.stardict/dic`
    * `tar jxf stardict-langdao-ce-gb-2.4.2.tar.bz2 -C ~/.stardict/dic`
- Download this [workflow](https://raw.githubusercontent.com/ruoshan/stardict-alfredworkflow/master/StarDict.alfredworkflow)
