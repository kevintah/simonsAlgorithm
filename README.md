# simonsAlgorithm
This is an implementation of Simon's  Quantum Algorithm in Qiskit from the ground up

                                                            ┌───┐ ░                      ░        ░ ┌───┐ ░ ┌─┐   
                                                       q_0: ┤ H ├─░───■────■─────────────░────────░─┤ H ├─░─┤M├───
                                                            ├───┤ ░   │    │             ░        ░ ├───┤ ░ └╥┘┌─┐
                                                       q_1: ┤ H ├─░───┼────┼────■────■───░────────░─┤ H ├─░──╫─┤M├
                                                            └───┘ ░ ┌─┴─┐  │  ┌─┴─┐  │   ░ ┌─┐    ░ └───┘ ░  ║ └╥┘
                                                       q_2: ──────░─┤ X ├──┼──┤ X ├──┼───░─┤M├────░───────░──╫──╫─
                                                                  ░ └───┘┌─┴─┐└───┘┌─┴─┐ ░ └╥┘┌─┐ ░       ░  ║  ║ 
                                                       q_3: ──────░──────┤ X ├─────┤ X ├─░──╫─┤M├─░───────░──╫──╫─
                                                                  ░      └───┘     └───┘ ░  ║ └╥┘ ░       ░  ║  ║ 
                                                       c: 4/════════════════════════════════╩══╩═════════════╩══╩═
                                                                                            0  1             2  3 
