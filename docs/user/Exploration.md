# Proof Exploration 

-- *Author: Sarah Grebing, Alexander Weigl*, XX.XX.2019 valid for KeY-2.10.0

!!! abstract
   
    This note describes the *Proof Exploration* features in KeY-2.10
   
   
   
## Overview 

We aggregrate under Proof Exploration, actions and views for supporting
a *What-If* analysis. With the here described actions you can investigate the
proof state and try to figure why a proof does not close.

For this we offer following actions:

* Add a formulae to the antecedent or succedent of a sequent. 
* Edit a formulae (or subterm) on a sequent
* Delete formulae from the sequent

Proof Nodes, which are affected of exploration actions, are marked in the Proof Tree.

!!! attention

    Proof Exploration actions are only available if you 
    activate the *Exploration Mode* in the toolbar.

## Actions

* AddFormulaToSuccedentAction
* AddFormulaToAntecedentAction
* DeleteFormulaAction
* EditFormulaAction
* ShowSecondBranchAction
* ToggleExplorationAction


## Views

![Image of Exploration Steps]()

Visualization of performed exploration actions. To jump to a node where the
action was applied to select the entry in the list or the tree view. To prune
exploration actions simply select an action and all action below this action
(visible in the tree visualization) are removed.