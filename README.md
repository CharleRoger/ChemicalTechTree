# Chemical Tech Tree

![[chemical-tech-tree-header.png]](https://raw.githubusercontent.com/CharleRoger/ChemicalTechTree/Screenshots/chemical-tech-tree-header.png)

A tech tree extension mod which adds a progression through propellants and other chemicals, parallel to the main tech tree.

This mod is part of the Chemical Technologies suite and is utilised by [Chemical Propulsion (1.6+)](https://github.com/CharleRoger/ChemicalPropulsion).

Each node of the Chemical Tech Tree contains a single part upgrade which is disabled by default and must be activated via a ModuleManager patch to appear in the game:
```
@PARTUPGRADE[chemical-tech-tree-partupgrade-LqdMethane]
{
	%chemTechActive = true
}
```

## Dependencies

- [Chemical Core (1.5.0)](https://github.com/CharleRoger/ChemicalCore)
- [ModuleManager (4.2.3)](https://github.com/sarbian/ModuleManager)
- [Community Resource Pack (112.0.1)](https://github.com/UmbraSpaceIndustries/CommunityResourcePack)
- [Hide Empty Tech Tree Nodes (1.3.2)](https://github.com/Orthethac/HideEmptyTechTreeNodes)

## Compatibility

Chemical Tech Tree is entirely separate to the main tech tree, so is functionally compatible with any other tech tree mod.

The positions of the tech tree nodes are adjusted to fit nicely together for the following tech trees:

[Community Tech Tree (3.4.5)](https://github.com/post-kerbin-mining-corporation/CommunityTechTree) and any other tech with the same structure, e.g. [Probes Before Crew (3.0.0)](https://forum.kerbalspaceprogram.com/topic/181013-ksp-18-112-probes-before-crew-pbc-version-293)
![[chemical-tech-tree-CommunityTechTree.png]](https://raw.githubusercontent.com/CharleRoger/ChemicalTechTree/Screenshots/chemical-tech-tree-CommunityTechTree.png)

[CSI Tech Tree (0.5.1)](https://forum.kerbalspaceprogram.com/topic/202292-1122-csi-tech-tree-05-usi-suite-updated)
![[chemical-tech-tree-CSITechTree.png]](https://raw.githubusercontent.com/CharleRoger/ChemicalTechTree/Screenshots/chemical-tech-tree-CSITechTree.png)

[Gradual Progression Tech Tree (0.3.3)](https://github.com/hersfeldtn/GPTT)
![[chemical-tech-tree-GradualProgressionTechTree.png]](https://raw.githubusercontent.com/CharleRoger/ChemicalTechTree/Screenshots/chemical-tech-tree-GradualProgressionTechTree.png)

[Kiwi Tech Tree (1.4.0)](https://github.com/hemeac/kiwiTechTree)
![[chemical-tech-tree-KiwiTechTree.png]](https://raw.githubusercontent.com/CharleRoger/ChemicalTechTree/Screenshots/chemical-tech-tree-KiwiTechTree.png)

[QUARTIX Tech Tree (3.13)](https://forum.kerbalspaceprogram.com/topic/174731-1125-techtrees-quartix-313-tetrix-230-simplex-140)
![[chemical-tech-tree-QUARTIXTechTree.png]](https://raw.githubusercontent.com/CharleRoger/ChemicalTechTree/Screenshots/chemical-tech-tree-QUARTIXTechTree.png)

[SIMPLEX Tech Tree (1.40)](https://forum.kerbalspaceprogram.com/topic/174731-1125-techtrees-quartix-313-tetrix-230-simplex-140)
![[chemical-tech-tree-SIMPLEXTechTree.png]](https://raw.githubusercontent.com/CharleRoger/ChemicalTechTree/Screenshots/chemical-tech-tree-SIMPLEXTechTree.png)

[Tech Tree Kompacted (1.6.1)](https://forum.kerbalspaceprogram.com/topic/199096-1123-techtree-kompacted-16-the-rp-1-edition)
![[chemical-tech-tree-TechTreeKompacted.png]](https://raw.githubusercontent.com/CharleRoger/ChemicalTechTree/Screenshots/chemical-tech-tree-TechTreeKompacted.png)

[TETRIX Tech Tree (2.30)](https://forum.kerbalspaceprogram.com/topic/174731-1125-techtrees-quartix-313-tetrix-230-simplex-140)
![[chemical-tech-tree-TETRIXTechTree.png]](https://raw.githubusercontent.com/CharleRoger/ChemicalTechTree/Screenshots/chemical-tech-tree-TETRIXTechTree.png)

[UnKerballed Start (1.3.2)](https://github.com/theonegalen/UnKerballedStart)
![[chemical-tech-tree-UnKerballedStart.png]](https://raw.githubusercontent.com/CharleRoger/ChemicalTechTree/Screenshots/chemical-tech-tree-UnKerballed.png)

Chemical Tech Tree is also compatible with [Skyhawk Science System (1.1.2)](https://github.com/CessnaSkyhawk/SkyhawkScienceSystem), but the part upgrades are integrated into the main tech tree rather than in separate nodes like the above, since the Skyhawk tech tree is designed with propellant-unlock nodes already.

## License

Distributed under the GNU General Public License.