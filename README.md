# An-FTCS-mode-of-solving-flux-equation
Generally, von Neumann stability analysis will failed in FTCS mode to solving the 1D flux equation. If we replace u(t,x) by (u(t,x+1)+u(t,x-1))/2 in the time derivative, the stability analysis will be valid when v*(delta_t)/(delta_x)<1.
