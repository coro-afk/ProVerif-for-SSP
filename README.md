# ProVerif-for-SSP
Here is the relevant code for the paper “Modeling Partially-Secure Channels for Bluetooth Secure Simple Pairing”.
These codes are modified from “Model Implementation and Attack Trace Explanation,” https://github.com/purseclab/btmodel_proverif.

## File explanation
SSP+DPE+DPENC/model/SSP+DEP+DPENC.pv contains the models of SSP, DPE, and DPENC.
SSP+DPE+DPENC/verify(SSP+DPE+DPENC).sh verifies the authentication properties A1 and A2 shown in Table 1 of the paper.

aex_apex/model/aex_ssp.pv contains the models of SSP, DPE, and DPENC in the AEX channel model.
aex_apex/aexverify(SSP+DPE+DPENC).sh verifies the authentication properties AEX-A1 and AEX-A2 shown in Table 1 of the paper.

cex_apex/model/cex_ssp.pv contains the models of SSP, DPE, and DPENC in the CEX channel model.
cex_apex/cexverify(SSP+DPE+DPENC).sh verifies the authentication properties CEX-A1 and CEX-A2 shown in Table 1 of the paper.

For more detail information see https://github.com/purseclab/btmodel_proverif/blob/main/README.md.
