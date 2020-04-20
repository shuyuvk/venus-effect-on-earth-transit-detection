# venus-effect-on-earth-transit-detection
the goal of the Earth 2.0 mision is to detect planets ("earths") by studying light decrease as the planet transits in front of its star and folding this data to find repeating dips (the star will be emitting high levels of noise). Both the 4 years of Kepler data and another 4 years of Earth 2.0 data will be used. 

However, the existence of another nearby planet in the studied system (a "venus") could affect the orbit of the "earth" enough that detectance is made more difficult. This code first records how large the variation in transit time would be (in hours) each year over 19 years (4 years of Kepler data, 11 blank years and 4 years of mission data). These influenced transits are then compared to the same system when not influenced by "venus". The signal to noise ratio for both of these systems are found and graphed along with the semi-major axis and eccentricity of the cases in order to find a correlation. 

Results are as expected. While some orbit systems may be influenced by "venus" and exhibit a significantly higher signal to noise ratio, the majority of the cases are still detectable.
