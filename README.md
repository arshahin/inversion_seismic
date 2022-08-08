# inversion_seismic

A package for the inversion of pre-stack seismic data using large-scale VFSA optimization 

I will place the codes in this repo soon. For now, enjoy reading the follwoing paper (PDF is provided too). 

Shahin, A., Stoffa, P.L., Myers, M.T., 2020, Stochastic seismic-wavelet inversion toward carbonate quantitative interpretation, 82nd EAGE Annual meeting, Amsterdam. 

A relevant repo to this one is my wavelet classification repo using CNN. Check it out here: https://github.com/arshahin/Wavelet_Classification_CNN

Abstarct for this repo (taken from paper): 

A seismic inversion algorithm is proposed to simultaneously retrieve P&S-wave velocities, density, and wavelet characteristics (shape and phase). Conditioned and NMO-corrected pre-stack seismic gathers in time and slowness domains are the main input. Inversion process can be executed in two different modes by replicating either NMO-corrected or raw synthetic gathers. In the latter mode, raw gathers are generated and NMO-correction is applied internally on raw gathers using intermediate P-wave velocity in each iteration. Full elastic reflectivity is the forward modelling algorithm utilized to replicate pre-stack seismic gathers. Very fast simulated annealing (VFSA) is the special global optimization algorithm employed to minimize objective function. The optimization algorithm is stochastic in nature and is enable to estimate uncertainty in model parameters. Unlike commercial software, no assumption is made on correlations between P&S-wave velocities and density. No smoothed background model is needed and only bounds on model parameters are necessary. The proposed workflow is claimed to recover sharp boundaries. This is due to the fact that non-liner full elastic reflectivity is used instead of linearized Zoeppritz equations. Thin beds are also recovered for the same reason and because of high resolution model parameters provided by stochastic component of the workflow.
