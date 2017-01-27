Note=This file is presented in roughly the order in which the page is built.  The "Model.Root" expands into the list of the divisions of the document, the divisions expand into sections, etc.

Head.EffectiveDate.sec={_Date_Effective}: {EffectiveDate.YMD}

Among.Ti/2=Entre :

Among.Ti/3=Entre :

Among.secs/2=<ul type="none" style="padding-left: 0"><li>{P1.FR.Contract.Among.Sec}</li><li>{P2.FR.Contract.Among.Sec}</li></ul>

Among.Secs/3=<ul type="none" style="padding-left: 0"><li>{P1.FR.Contract.Among.Sec}</li><li>{P2.FR.Contract.Among.Sec}</li><li>{P3.FR.Contract.Among.Sec}</li><li>{P4.FR.Contract.Among.Sec}</li></ul>

Among.Secs/4=<ul type="none" style="padding-left: 0"><li>{P1.FR.Contract.Among.Sec}</li><li>{P2.FR.Contract.Among.Sec}</li><li>{P3.FR.Contract.Among.Sec}</li><li>{P4.FR.Contract.Among.Sec}</li></ul>

Among.Def.sec=Dénommés individuellement une « {_partie} » et collectivement les « {_parties} »
 
Note=Friends.Div is for documents that need to list other persons, for instance affiliates of one of the parties.  Defaults to null.  To use it, define a paragraph with the desired number of referenced persons in the format "Friend.=[Z/ol/s*]" where * is the number of persons, e.g, "Friend.=[Z/ol/s3]".  This uses the common paragraph format widget.

Friend.Def.sec=Dénommés individuellement une « {_Tierce_Identifiée} » et collectivement les « {_Tierces_Identifiées} »

Note=This.* is the part that usually starts with "This Agreement ...."

This.sec/2=Entre les {_parties} :

This.sec/3=Entre les {_parties} :

Why.Ti=Etant préalablement rappelé que :

That.sec=Il a été convenu et arrêté ce qui suit :

Note=Sec.* is the sections of the agreement - the principal text.  There is an option for a heading, but that is rare.  We also include a default set of top-level subject matter divisions.

By.Ti=Signature

By.0.sec=Fait à lieu de conclusion de l'{_Accord}, le {DateSignature.YMD}.

By.secs/2=<table><tr><td valign=top>{P1.FR.Contract.By.Sec}</td><td valign=top>   </td><td valign=top>{P2.FR.Contract.By.Sec}</td></tr></table>

By.secs/3=<table><tr><td valign=top>{P1.FR.Contract.By.Sec}</td><td valign=top>   </td><td valign=top>{P2.FR.Contract.By.Sec}</td></tr><tr><td valign=top>{P3.FR.Contract.By.Sec}</td><td valign=top>   </td><td valign=top></td></tr></table>

By.secs/4=<table><tr><td valign=top>{P1.FR.Contract.By.Sec}</td><td valign=top>   </td><td valign=top>{P2.FR.Contract.By.Sec}</td></tr><tr><td valign=top>{P3.FR.Contract.By.Sec}</td><td valign=top>   </td><td valign=top>{P4.FR.Contract.By.Sec}</td></tr></table>
 
Annex.Ti=Annexes

Note=The Oxford comma.  Establishing the default as no such comma.  But can override in your documents.

q=</i>

=[GH/CommonAccord/Form-Agt/00.md]
