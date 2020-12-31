Contains hashes to current research not ready for publishing. Used as proof of authorship at time T.

#### Hashes:
`$ find projects -type f -exec sha512sum {} \;|sort > projects_hashes.$(date "+%Y.%m.%d-%H.%M.%S")`\
`$ sha512sum projects_hashes.$(date "+%Y.%m.%d-%H.%M.%S")`
794264206b920ae1f7ba33d85f932b9dd1dbcbdbd0b892b529ab10bedfc6409bb99e67b5b06777ac7213ac3333f85a6d85c06ecf183b958202612bba09e08f79  projects_hashes.2020.12.30-02.49.48
c1672644c60e4a956eda995e38b6eb09e4f12004e7026cda3348e26f084bdd464311e8b27506818f9f453252b560fa05c469305a4b776cb3137a1a99001ddff4  project_archive.2020.12.30-02.49.48.7z

01d47b168ab6619f317de10593658ba37e7c5109effa5c88a375af779509c0ff64f6ad966027345a55f69c2e65f95f7f7798fb6dc1bcf067eaae3ca0da8a9ae2  archive_research_old_work_and_notes_hashes.2020.12.31-14.55.57
30a4312c99007b31329bcbe773272ceb594d9f300fc2c9a61201b3487eacdcfa0b1d27128564741a9a57d09cc0cfff4bfbaa4fceb7fdc10ba2292c8afc39eddf  archive_research_old_work_and_notes_with_hashes.7z
