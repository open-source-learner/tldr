# cargo

> Gestion d'un projet Rust et ses dependences (crates).
> Certaines sous-commandes comme `build` ont leurs propres documentations.
> Plus d'informations : <https://doc.rust-lang.org/stable/cargo/>.

- Recherche des crates :

`cargo search {{recherche}}`

- Installe un crate :

`cargo install {{nom_du_crate}}`

- Liste les crates déjà installés :

`cargo install --list`

- Crée un nouveau binaire ou librairie du projet Rust dans les dossiers spécifiés (ou dans le dossier courant par défaut) :

`cargo init --{{bin|lib}} {{chemin/vers/dossier}}`

- Compile le projet Rust dans le dossier courant en utilisant le profil release :

`cargo {{[b|build]}} {{[-r|--release]}}`

- Compile le projet Rust dans le dossier courant en utilisant le compilateur nightly :

`cargo +nightly {{[b|build]}}`

- Compile en utilisant un nombre spécifique de threads (par défaut on prend le nombre de coeurs du CPU) :

`cargo {{[b|build]}} {{[-j|--jobs]}} {{nombre_de_threads}}`
