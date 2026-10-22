# Physics Notes

I wrote these notes while learning many-body theory and quantum magnetism. Writing a derivation out in full, and checking every step in Mathematica, was how I made sure I actually understood it. I'm sharing them in case they help someone working through the same material.

## Notes

| Notes | What it covers |
|---|---|
| [Green's Function Methods](Many-body-Theory/Many-body-theory-Greens-function-method.pdf) (204 pp.) | Fermi liquid theory, linear response and the Kubo formula, analytic properties of susceptibilities, screening (Thomas–Fermi, Lindhard/RPA), conductivity, Drude weight, and what makes a metal, an insulator or a superconductor. |
| [Review on Theory of Superexchange](Superexchange/Theory-of-superexchange.pdf) (23 pp.) | From Heitler–London and Dirac exchange to Anderson's superexchange, the Goodenough–Kanamori–Anderson rules, effective spin models from downfolding, Dzyaloshinskii–Moriya interaction and ring exchange. |

The Green's function notes follow published lectures and textbooks closely, mainly [Giamarchi's notes](https://arxiv.org/abs/1007.1030), Tremblay's *Quantum Materials Theory*, Mahan's *Many-Particle Physics* and Altland & Simons. Each section names its source.

## Mathematica notebooks

These are the checks and plots that go with the notes.

- `Many-body-Theory/mma/`: Lindhard function in d = 1, 2, 3, Friedel oscillations, Kramers–Kronig relations, susceptibility poles, irreversibility from infinitely many harmonic oscillators, Compton profile J(Q), a Hartree–Fock pathology, and exact diagonalization of small Hubbard rings (2 to 6 sites).
- `Superexchange/super-exchange.nb`: derives the effective spin Hamiltonian for two electrons by downfolding and second-order quasi-degenerate perturbation theory, including the DM term.

Several notebooks use [SNEG](https://nrgljubljana.ijs.si/sneg/), Rok Žitko's Mathematica package for second-quantized operator algebra.

## Feedback and videos

If you find a mistake, please open an issue or email me at liukelyu@gmail.com.

I also make videos on theoretical physics (in Chinese) on [Bilibili](https://b23.tv/7l9wcZ9).

## License

My own text and notebooks are licensed under [CC BY 4.0](LICENSE). Material quoted from the sources cited above stays under its authors' terms.
