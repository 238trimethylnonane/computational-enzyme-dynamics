    # computational-enzyme-dynamics
    import numpy as np
    import matplotlib.pyplot as plt
    Vmax = 1.0
    Km = 2.0

    S = np.linspace(0, 10, 100)  # substrate concentrations
    def michaelis_menten(S, Vmax, Km):
        return (Vmax * S) / (Km + S)
    v = michaelis_menten(S, Vmax, Km)
    v = michaelis_menten(S, Vmax, Km)
    noise = np.random.normal(0, 0.05, size=S.shape)
    v_noisy = v + noise
    plt.figure()
    plt.scatter(S, v_noisy, label="Simulated data", alpha=0.5)
    plt.plot(S, v, label="True Michaelis-Menten curve")
    plt.xlabel("Substrate concentration [S]")
    plt.ylabel("Reaction rate v")
    plt.title("Enzyme Kinetics Simulation")
    plt.legend()
    plt.show()
    import pandas as pd
    import numpy as np
    from sklearn.cluster import KMeans
    import matplotlib.pyplot as plt
    from sklearn.decomposition import PCA
    from sklearn.preprocessing import StandardScaler
    scaler = StandardScaler()
    X_scaled = scaler.fit_transform(data.T)  # samples × genes
    plt.figure()
    plt.scatter(X_pca[:,0], X_pca[:,1], c=labels)
    plt.xlabel("PC1")
    plt.ylabel("PC2")
    plt.title("Gene Expression PCA")
    plt.show()
    loading_scores = pca.components_[0]
    top_genes = np.argsort(np.abs(loading_scores))[-10:]
