# Fairness without the Sensitive Attribute via Causal Variational Autoencoder

This work has been accepted at the IJCAI 2022 conference.

https://www.ijcai.org/Proceedings/2022/0098.pdf

In recent years, most fairness strategies in machine learning have focused on mitigating unwanted biases by assuming that the sensitive information is
available. However, in practice this is not always the case: due to privacy purposes and regulations such as RGPD in EU, many personal sensitive attributes are frequently not collected. Yet, only a
few prior works address the issue of mitigating bias in this diffcult setting, in particular to meet classical fairness objectives such as Demographic
Parity and Equalized Odds. By leveraging recent developments for approximate inference, we propose in this paper an approach to fll this gap. To
infer a sensitive information proxy, we introduce a new variational auto-encoding-based framework named SRCVAE that relies on knowledge of the
underlying causal graph. The bias mitigation is then done in an adversarial fairness approach. Our proposed method empirically achieves signifcant improvement over existing works in the feld. We observe that the generated proxy’s latent space correctly recovers sensitive information and that our
approach achieves a higher accuracy while obtaining the same level of fairness on two real datasets.


![alt text](https://github.com/[username]/[reponame]/blob/[branch]/image.jpg?raw=true)
