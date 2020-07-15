°°MlD


Universite (id_u, nom_u, nom_cli, logo_u, contact_u, user_nom_u, user_prenom_u, user_email_u, user_mdp_u, user_photo_u,date_add_u)

Ufr (id_ufr,id_u, nom_ufr, libele_ufr, date_add_ufr)

Cycle (id_c, nom_c, date_add_c)

Filiere (id_f, id_c,id_ufr, nom_f,libele_f,photo_f ,date_add_f)

Niveau (id_niv, nom_niv, date_add_niv)

Classe (id_cls,id_niv, id_f, libele_cls, date_add_cls) 

Ue(id_ue, id_cls, nom_ue, libele_ue , photo_ue , date_add_ue)

Instructeur(id_ins , user_nom__ins , user_prenom__ins, user_email__ins , user_mdp__ins , user_photo_ins, user_diplome_ins , user_contact_ins, user_addresse_ins , date_add_ins )

Ucue(id_ucue, id_ins, id_ue , nom_ucue , libele_ucue , photo_ucue , video_intro_ucue , description_ucue , prix_ucue , date_add_ucue)

Lecon(id_l ,id_ucue , description_l ,date_add_l )

TypeRessource(id_tr , titre_tr , date_add_tr)

RessourceLesson(id_rs , id_tr ,id_l, titre_rs , lien_rs , date_add_rs )

Etudiant(id_etud , nom_etud , prenom_etud , email_etud , mdp_etud , photo_etud , statpro_etud , contact_etud , addresse_etud , birthday_etud, certificat_etud , date_add_etud)

Annee_Academique(id_ac , encour_ac , passer_ac , date_add_ac )

-parcours(id_parc , id_etud , id_cls, id_ac)

Alumni( id_al , id_etud , fonction_al , nom_entreprise_al ,date_add_al )

DemandeInscription(id_di ,id_ac , id_cls, nom_di ,prenom_di ,email_di, contact_di , valider_di , refuser_di , date_add_di )

-Achat_Cours(id_ach , id_ucue , id_etud)

-Resultat_année(id_ra ,id_ue,id_parc)
