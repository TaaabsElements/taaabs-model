# taaabs-model

`<taaabs-model>` is a set of Polymer Customs Elements to display a graphical representation of a KTBS Model.

More information about <a href="https://kernel-for-trace-based-systems.readthedocs.org/en/latest/concepts/trace_model.html">KTBS Bases</a>.
More information about <a href="https://kernel-for-trace-based-systems.readthedocs.org/en/latest/concepts/abstract_api.html#model-resource">KTBS Bases API</a>.

This Polymer Custom Element contains two other Polymer Custom Element.

(@see) `<taaabs-display-model>`

(@see) `<taaabs-obsel-inspector-type>`

(@see) Samotraces.Ktbs.Model : Model (in the MVC pattern)

(@see) Samotraces.Selector : Model (in the MVC pattern)
More information about <a href="http://dsi-liris-silex.univ-lyon1.fr/bmathern/samotraces/doc/Samotraces.Selector.html#toc0">Samotraces.Selector</a>. TODO Need update

We use it to store a selection of objects
(@polymerBehavior) TaaabsBehaviors.TraceToModel : Polymer Behavior (Mixin)
We use it to generate a model from a trace data
@element taaabs-model
