\begin{section}{title="About"}
# Ian C. Weaver, Ph.D.
\html{<a href="https://www.linkedin.com/in/icweaver/" target="_blank"><i class="fa-brands fa-linkedin" style="font-size:1.5rem"></i></a>}
\html{<a href="https://github.com/icweaver/" target="_blank"><i class="fa-brands fa-github" style="font-size:1.5rem"></i></a>}
\html{<a href="mailto:weaveric@gmail.com" target="_blank"><i class="fa fa-envelope" style="font-size:1.5rem"></i></a>}
\html{<img align="right" src="/assets/profile.jpg" id="hp" width=20%>}

Hi, I'm Ian, a recent PhD from the \link{Center for Astrophysics | Harvard &
Smithsonian}{https://pweb.cfa.harvard.edu/}. I focused on studying large exoplanets with \link{large
telescopes}{https://obs.carnegiescience.edu/Magellan} and writing software to analyze them. I worked on all stages of
the process, including extraction and reduction of the raw \link{time series spectral
data}{http://astro.dur.ac.uk/~knpv27/pg_dr_course/pg_dr_spectroscopy.html}, detrending of potential signals via
different Gaussian Process \link{(GP)}{https://en.wikipedia.org/wiki/Gaussian_process} and Principal Component Analysis
\link{(PCA)}{https://en.wikipedia.org/wiki/Principal_component_analysis} techniques, and the applications of a range of
statistical Bayesian inference frameworks including Markov chain Monte Carlo
\link{(MCMC)}{https://en.wikipedia.org/wiki/Markov_chain_Monte_Carlo} and \link{nested
sampling}{https://en.wikipedia.org/wiki/Nested_sampling_algorithm} to study the atmospheres of these other worlds.

In my free time, I love rowing, participating in \link{STEM outreach}{https://www.onaketa.org/} in
underrepresented communities, and
\link{learning more about Julia}{https://exercism.org/profiles/icweaver/testimonials} with other folks!

Résumé:
\link{<i class="fa fa-rectangle-list"></i>}{/assets/resume.pdf} |
CV:
\link{<i class="fa fa-book-open"></i>}{/assets/cv.pdf} |
NASA ADS:
\link{<i class="fa fa-rocket"></i>}{https://ui.adsabs.harvard.edu/public-libraries/6nMcPukqSpiQq_0Ak7g8sA}
\end{section}

\begin{section}{title="Projects"}

# Tutor-mentor / student matching
\html{
<a href="https://github.com/icweaver/onaketa/tree/main/matching" target="_blank"><i class="fa-brands fa-github" style="font-size:1.5rem"></i></a>
<a href="https://icweaver.github.io/onaketa/matching/matching.jl.html" target="_blank"><i class="fa fa-book" style="font-size:1.5rem"></i></a>
}

As a tutor coordinator, I was looking for an efficient way to match tutor-mentors with students. This turned into a fun
weekend project turning the raw data from the awesome scheduling tool [WhenIsGood](https://whenisgood.net/) into a colorful matching matrix showing the common
overlap in different people's schedules.

\begin{columns}
\begin{column}{}
**_WhenIsGood_**
\figure{
    path = "/assets/whenisgood.png",
    caption = "An example of the site seen on the user's end. Just click and drag over your availability and submit when
    you are done. The unix timestamps for the entries from each user is stored at the bottom of the results page HTML within
    a javascript tag. I extract this data in the next step to create the following visualization."
}
\end{column}

\begin{column}{}
**_Matching Matrix_**
\figure{
    path = "/assets/scheduler.png",
    caption = "This is the resulting matching matrix seen on the tutor coordinator's end. The data is automatically
    downloaded, extracting, and post-processed to display the intersections between available dates/times for
    all tutor-mentor / student combinations. A handy tooltip also displays the overlapping
    times for a given tutor-mentor / student pair, which is automatically copied to the clipboard at the click of a
    mouse."
}
\end{column}
\end{columns}

# Exoplanets

Data wrangling/visualization of publicly available exoplanet data, with [Julia](https://julialang.org/) and
\html{<a href="https://github.com/fonsp/Pluto.jl">Pluto.jl</a>}.

\begin{columns}
\begin{column}{}
**_Exoplanet locator_**
\html{<a href="https://github.com/icweaver/Pluto_sample_notebooks/blob/main/astroimages.jl" target="_blank"><i class="fa-brands fa-github" style="font-size:1.0rem"></i></a>}
\html{<a href="https://icweaver.github.io/Pluto_sample_notebooks/astroimages.html" target="_blank"><i class="fa fa-book" style="font-size:1.0rem"></i></a>}
  \figure{
    path = "/assets/constellations.svg",
    caption = "A groovy exoplanet sky chart created with data queried from the exoplanet archive, bright star locations from the Hipparcos, Yale Bright Star, Gliese (HYG) database, and asterisms from the Stellarium public repo."
  }
\end{column}

\begin{column}{}
**_System parameters calculator_**
\html{<a href="https://github.com/icweaver/ExoCalc.jl" target="_blank"><i class="fa-brands fa-github" style="font-size:1.0rem"></i></a>}
\html{<a href="https://icweaver.github.io/ExoCalc.jl/" target="_blank"><i class="fa fa-book" style="font-size:1.0rem"></i></a>}
  \figure{
    path = "/assets/exocalc.png",
    caption = "Self-consistent computations of exoplanet parameters from stellar and orbital observations. Useful for
    estimating the potential observability of an exoplanet's atmopshere."
  }
\end{column}
\end{columns}

\html{<br>}

# spacejam
\html{
<a href="https://github.com/cs207-SpaceJam/cs207-FinalProject" target="_blank"><i class="fa-brands fa-github" style="font-size:1.5rem"></i></a>
<a href="https://spacejam.readthedocs.io/en/latest/index.html" target="_blank"><i class="fa fa-book" style="font-size:1.5rem"></i></a>
}

Python package for numerical integration, powered by [automatic differentiation](https://en.wikipedia.org/wiki/Automatic_differentiation).

\begin{columns}
\begin{column}{}
**_Orbital trajectories_**
\html{
<div id="outer">
<video controls width="100%">
  <source src="/assets/exo-moon.mp4" type="video/mp4" caption="yee">
  Sorry, your browser doesn't support embedded videos.
</video>
</div>
}

Integrated orbit of a hypothetical three-body star-planet-moon system via s=2 Adams-Moulton method. This is motivated by
the first potential discovery of an exomoon made not too long ago.
\end{column}

\begin{column}{}
**_Population dynamics_**
\html{
<div id="outer">
<video controls width="100%">
  <source src="/assets/ecology.mp4" type="video/mp4">
  Sorry, your browser doesn't support embedded videos.
</video>
</div>
}

The same integration method applied to the Lotka–Volterra system of differential equations describing population growth.
\end{column}
\end{columns}

\html{<br>}

# Accretion stream toy model
\html{
<a href="https://github.com/icweaver/particle_trajectory" target="_blank"><i class="fa-brands fa-github" style="font-size:1.5rem"></i></a>
}

Orbital dynamics code written in Fortran, visualized in Python.

\begin{columns}
\begin{column}{}
**_Artificial energy loss_**
\html{
<div id="outer">
<img src="/assets/sho_inertial_3D.gif" width="100%" alt="Banner Image"/>
</div>
}

Particle stream trajectory in a binary Roche Potential with artificial energy loss every time step to mimic the energy
that is lost to shocks and other collisions in real fluid interactions. This was done by having the test particle lose
energy while maintaining its angular momentum. I also added a little kick in the z component of the particle's initial
velocity to make it a little more fun to watch.
\end{column}

\begin{column}{}
**_WASP-12/b system_**
\html{
<div id="outer">
<img src="/assets/xy.png" width="100%" alt="Banner Image"/>
</div>
}

Top-down view of the same code applied to WASP-12/b (to scale). I waited until a full orbit to turn on the artificial
energy loss to mimic one full lap of the accretion stream before colliding with itself. The corners due to the Coriolis
force are clearly seen and the orbit settles down into its circularization radius (in green), as predicted from angular
momentum conservation.
\end{column}
\end{columns}

\html{<br>}

# Accretion disk fluid simulations

Hydrodynamical simulations of planetary cannibalism made with [FLASH](https://flash.rochester.edu/site/flashcode/).

\begin{columns}
\begin{column}{}
**_WASP-12/b 2D_**
\html{
<div id="outer">
<video controls width="100%">
  <source src="/assets/dens_2d.mp4" type="video/mp4">
  Sorry, your browser doesn't support embedded videos.
</video>
</div>
}

An analog to the toy-model from the particle trajectory code above. I replaced the massless test particle in that code
with a fluid outflow boundary, following properties adopted from Lai et al. (2010). I then added an artificial ramp up
in density at around the 5 day mark to effectively fast-forward the disk to a more evolved state.
\end{column}
\begin{column}{}
**_WASP-12/b 3D_**
\html{
<div id="outer">
<img src="/assets/3d_disk.png" width="100%" alt="Banner Image"/>
</div>
}

I adapted the hydro simulation to 3D to create the image above. This is an isodensity contour plot taken partway through
the simulation. The location of L1 can be seen as the orange-yellow sphere towards the bottom left. These simulations
were used to create virtual light curves to compare with observations from HST's Cosmic Origins Spectrograph.
\end{column}
\end{columns}
\end{section}

\begin{section}{title="Research"}
# WASP-50b (Weaver et al. submitted)
\html{
<a href="https://github.com/icweaver/WASP-50b" target="_blank"><i class="fa-brands fa-github" style="font-size:1.5rem"></i></a>
<a href="https://icweaver.github.io/WASP-50b/" target="_blank"><i class="fa fa-book" style="font-size:1.5rem"></i></a>
}
\begin{columns}
\begin{column}{}

  \figure{
    path = "/assets/w50_left.svg",
    caption = ""
  }
\end{column}

\begin{column}{}

  \figure{
    path = "/assets/w50_right.svg",
    caption = ""
  }
\end{column}
\end{columns}

We present a new **ground-based visual transmission spectrum** of the hot Jupiter WASP-43b, obtained as part of
**ACCESS**. We collected four transits observed between 2015 and 2018, with a combined wavelength coverage between
5300 and 9000 Å and an average photometric precision of 708 ppm in 230 Å bins. We perform an **atmospheric
retrieval** of our transmission spectrum combined with literature Hubble Space Telescope/WFC3 observations to search
for the presence of clouds/hazes as well as Na, K, Hα, and H₂O planetary absorption and stellar spot contamination.
**We do not detect a statistically significant presence of Na I or K I alkali lines, or Hα in the atmosphere of
WASP-43b**. We find that the observed transmission spectrum can be best explained by a combination of heterogeneities
on the photosphere of the host star and a **clear planetary** atmosphere with water.

# HAT-P-23b (Weaver et al. 2021)
\html{
<a href="https://github.com/icweaver/HAT-P-23b" target="_blank"><i class="fa-brands fa-github" style="font-size:1.5rem"></i></a>
<a href="https://icweaver.github.io/HAT-P-23b/" target="_blank"><i class="fa fa-book" style="font-size:1.5rem"></i></a>
<a href="https://ui.adsabs.harvard.edu/abs/2021AJ....161..278W/abstract" target="_blank"><i class="fa fa-newspaper" style="font-size:1.5rem"></i></a>
}
  \figure{
    path = "/assets/tspec_hatp23b.svg",
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

# WASP-43b (Weaver et al. 2020)
\html{
<a href="https://github.com/icweaver/ACCESS_notebook" target="_blank"><i class="fa-brands fa-github" style="font-size:1.5rem"></i></a>
<a href="https://ui.adsabs.harvard.edu/abs/2020AJ....159...13W/abstract" target="_blank"><i class="fa fa-newspaper" style="font-size:1.5rem"></i></a>
}
  \figure{
    path = "/assets/tspec_wasp43b.jpg",
    caption = "We present a new <b>ground-based visual transmission spectrum</b> of the hot Jupiter WASP-43b, obtained as
    part of <b>ACCESS</b>. We collected four transits observed between 2015 and 2018, with a combined wavelength coverage
    between 5300 and 9000 Å and an average photometric precision of 708 ppm in 230 Å bins. We perform an <b>atmospheric
    retrieval</b> of our transmission spectrum combined with literature Hubble Space Telescope/WFC3 observations to search
    for the presence of clouds/hazes as well as Na, K, Hα, and H₂O planetary absorption and stellar spot contamination.
    <b>We do not detect a statistically significant presence of Na I or K I alkali lines, or Hα in the atmosphere of
    WASP-43b</b>. We find that the observed transmission spectrum can be best explained by a combination of
    heterogeneities on the photosphere of the host star and a <b>clear planetary atmosphere</b> with water."
  }
\end{section}

\html{
<div class="main-header">
  <img src="/assets/c_and_h_banner.jpeg" width="100%" alt="Banner Image"/>
</div>
}

\html{
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <script src="https://kit.fontawesome.com/bd904155ad.js" crossorigin="anonymous"></script>
}
