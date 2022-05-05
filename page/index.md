\begin{section}{name="Projects"}
## Exoplanet sky visualizer

\begin{columns}
\begin{column}{}
\begin{center}
  \figure{
    path = "/assets/nice_image.jpg",
    caption = "Pluto.jl + AstroImages.jl = ❤"
  }
\end{center}
\end{column}
\end{columns}

## [`spacejam`](https://spacejam.readthedocs.io/en/latest/index.html)
Python package for numerical integration, powered by [automatic differentiation](https://en.wikipedia.org/wiki/Automatic_differentiation).

\begin{columns}
\begin{column}{}
**_Orbital trajectories_**
\begin{center}
  \figure{
    path = "/assets/nice_image.jpg",
    caption = "Integrated orbit of a hypothetical three-body star-planet-moon system via s=2 Adams-Moulton method.
    This is motivated by the first potential discovery of an exomoon made not too long ago."
  }
\end{center}
\end{column}

\begin{column}{}
**_Population dynamics_**
\begin{center}
  \figure{
    path = "/assets/nice_image.jpg",
    caption = "The same integration method applied to the Lotka–Volterra system of differential equations describing population growth."
  }
\end{center}
\end{column}
\end{columns}

## [Accretion stream toy model](https://github.com/icweaver/particle_trajectory)
\begin{columns}
\begin{column}{}
**_Artificial energy loss_**
\begin{center}
  \figure{
    path = "/assets/nice_image.jpg",
    caption = "Particle stream trajectory in a binary Roche Potential with artificial energy loss every time step. This
    was done to mimic the energy that is lost to shocks and other collisions in real fluid interactions. This was done
    by having the test particle lose energy while maintaining its angular momentum. I also added a little kick in the z
    component of the particle's initial velocity to make it a little more fun to watch."
  }
\end{center}
\end{column}

\begin{column}{}
**_WASP-12/b system_**
\begin{center}
  \figure{
    path = "/assets/nice_image.jpg",
    caption = "op-down plot of the same code applied to WASP-12/b (to scale). I waited until a full orbit to turn on the
    artificial energy loss to mimic one full lap of the accretion stream before colliding with itself. The corners due
    to the Coriolis force are clearly scene and the orbit settles down into its circularization radius (in green), as
    predicted from angular momentum conservation."
  }
\end{center}
\end{column}
\end{columns}

## Accretion disk fluid simulations
Below are hydrodynamical simulations made with [FLASH](https://flash.rochester.edu/site/flashcode/).

\begin{columns}
\begin{column}{}
**_WASP-12/b 2D_**
\begin{center}
  \figure{
    path = "/assets/nice_image.jpg",
    caption = "An analog to the toy-model from the particle trajectory code above. I
    replaced the massless test particle in that code with a fluid outflow boundary, following properties adopted from
    Lai et al. (2010). I then added an artificial ramp up in density at around the 5 day mark to effectively
    fast-forward the disk to a more evolved state."
  }
\end{center}
\end{column}
\begin{column}{}
**_WASP-12/b 3D_**
\begin{center}
  \figure{
    path = "/assets/nice_image.jpg",
    caption = "I adapted the hydro simulation to 3D to create the image above. This is an isodensity contour plot taken
    partway through the simulation. The location of L1 can be seen as the orange-yellow sphere towards the bottom left.
    These simulations were used to create virtual light curves to compare with observations from HST's Cosmic Origins
    Spectrograph."
  }
\end{center}
\end{column}
\end{columns}
\end{section}

\begin{section}{name="Research"}
## [WASP-50b (Weaver et al. submitted)](https://icweaver.github.io/WASP-50b/)
\begin{center}
  \figure{
    path = "/assets/nice_image.jpg",
    caption = "We present a new <b>ground-based visual transmission spectrum</b> of the hot Jupiter WASP-43b, obtained
    as part of <b>ACCESS</b>. We collected four transits observed between 2015 and 2018, with a combined wavelength
    coverage between 5300 and 9000 Å and an average photometric precision of 708 ppm in 230 Å bins. We perform an
    <b>atmospheric retrieval</b> of our transmission spectrum combined with literature Hubble Space Telescope/WFC3
    observations to search for the presence of clouds/hazes as well as Na, K, Hα, and H₂O planetary absorption and
    stellar spot contamination. <b>We do not detect a statistically significant presence of Na I or K I alkali lines, or
    Hα in the atmosphere of WASP-43b</b>. We find that the observed transmission spectrum can be best explained by a
    combination of heterogeneities on the photosphere of the host star and a <b>clear planetary</b> atmosphere with
    water."
  }
\end{center}

## [HAT-P-23b (Weaver et al. 2021)](https://icweaver.github.io/HAT-P-23b/README.html)
\begin{center}
  \figure{
    path = "/assets/nice_image.jpg",
    caption = "We present a new <b>ground-based visible transmission spectrum</b> of the <b>high-gravity, hot
    Jupiter</b> HAT-P-23b, obtained as part of the <b>ACCESS</b> project. We derive the spectrum from five transits
    observed between 2016 and 2018, with combined wavelength coverage between 5200 Å - 9269 Å in 200 Å bins, and with a
    median precision of 247 ppm per bin. HAT-P-23b's relatively high surface gravity (g ~ 30 m/s²), combined with
    updated stellar and planetary parameters from Gaia DR2, gives a 5-scale-height signal of 384 ppm for a
    hydrogen-dominated atmosphere. Bayesian models favor a <b>clear atmosphere for the planet with the tentative
    presence of TiO</b>, after simultaneously modeling stellar contamination, using spots parameter constraints from
    photometry. <b>If confirmed, HAT-P-23b would be the first example of a high-gravity gas giant with a clear
    atmosphere observed in transmission at optical/NIR wavelengths</b>; therefore, we recommend expanding observations
    to the UV and IR to confirm our results and further characterize this planet. This result demonstrates how combining
    transmission spectroscopy of exoplanet atmospheres with long-term photometric monitoring of the host stars can help
    disentangle the exoplanet and <b>stellar activity signals</b>."
  }
\end{center}

## [WASP-43b (Weaver et al. 2020)](https://ui.adsabs.harvard.edu/abs/2020AJ....159...13W/abstract)
\begin{center}
  \figure{
    path = "/assets/nice_image.jpg",
    caption = "We present a new <b>ground-based visual transmission spectrum</b> of the hot Jupiter WASP-43b, obtained as
    part of <b>ACCESS</b>. We collected four transits observed between 2015 and 2018, with a combined wavelength coverage
    between 5300 and 9000 Å and an average photometric precision of 708 ppm in 230 Å bins. We perform an <b>atmospheric
    retrieval</b> of our transmission spectrum combined with literature Hubble Space Telescope/WFC3 observations to search
    for the presence of clouds/hazes as well as Na, K, Hα, and H₂O planetary absorption and stellar spot contamination.
    <b>We do not detect a statistically significant presence of Na I or K I alkali lines, or Hα in the atmosphere of
    WASP-43b</b>. We find that the observed transmission spectrum can be best explained by a combination of
    heterogeneities on the photosphere of the host star and a <b>clear planetary atmosphere</b> with water."
  }
\end{center}
\end{section}

\begin{section}{title="CV/Resume"}
it me
\end{section}
