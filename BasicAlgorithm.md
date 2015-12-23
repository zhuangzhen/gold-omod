# Basic algorithm #

_Please note: this page relies on MathML. Firefox, Safari and most browsers will work. Some browsers may not._

The model equations are integrated forward in phases as follows.

## Adiabatic phase ##

The system is treated as adiabatic and assumes no exchange between layers (d<sub>t</sub> s = 0)

<wiki:gadget url="http://mathml-gadget.googlecode.com/svn/trunk/mathml-gadget.xml" border="0" up\_content="\partial\_{t} vec u\_h + frac{f+zeta}{h} hat k times h vec u\_h + grad\_s K + frac 1 rho grad\_s p = frac 1 rho grad\_s cdot ul ul tau " width="100%" up\_foreground="green"/>

<wiki:gadget url="http://mathml-gadget.googlecode.com/svn/trunk/mathml-gadget.xml" border="0" up\_content="\partial\_{t} h + grad cdot ( h vec u\_h ) + partial\_s ( h dot s ) = 0 " width="100%" up\_foreground="green"/>

<wiki:gadget url="http://mathml-gadget.googlecode.com/svn/trunk/mathml-gadget.xml" border="0" up\_content="delta\_k p + rho delta\_k Phi = 0" width="100%" up\_foreground="green"/>

where

<wiki:gadget url="http://mathml-gadget.googlecode.com/svn/trunk/mathml-gadget.xml" border="0" up\_content="K = frac 1 2 vec u\_h cdot vec u\_h" width="100%" up\_foreground="green"/>

## Tracer phase ##

The mass transports from the adiabatic phase are accumulated (time averaged) and now used to update tracers:

<wiki:gadget url="http://mathml-gadget.googlecode.com/svn/trunk/mathml-gadget.xml" border="0" up\_content="partial\_t ( theta h ) + grad cdot ( theta h vec u\_h ) = grad\_s cdot vec F\_q" width="100%" up\_foreground="blue"/>

<wiki:gadget url="http://mathml-gadget.googlecode.com/svn/trunk/mathml-gadget.xml" border="0" up\_content="partial\_t ( S h ) + grad cdot ( S h vec u\_h ) = grad\_s cdot vec F\_s" width="100%" up\_foreground="blue"/>


## Diabatic physics (or remapping) phase ##

Vertical physics is combined with motion of the layer interfaces {$(\dot{s})$} to update all variables:

<wiki:gadget url="http://mathml-gadget.googlecode.com/svn/trunk/mathml-gadget.xml" border="0" up\_content="partial\_t vec u\_h + s partial\_s vec u\_h = 0" width="100%" up\_foreground="red"/>

<wiki:gadget url="http://mathml-gadget.googlecode.com/svn/trunk/mathml-gadget.xml" border="0" up\_content="partial\_t h + partial\_s (h dot s) = 0" width="100%" up\_foreground="red"/>

<wiki:gadget url="http://mathml-gadget.googlecode.com/svn/trunk/mathml-gadget.xml" border="0" up\_content="partial\_t (theta h) + partial\_s (theta h dot s) = partial\_s F\_q^v " width="100%" up\_foreground="red"/>

<wiki:gadget url="http://mathml-gadget.googlecode.com/svn/trunk/mathml-gadget.xml" border="0" up\_content="partial\_t (S h) + partial\_s (S h dot s) = partial\_s F\_s^v " width="100%" up\_foreground="red"/>