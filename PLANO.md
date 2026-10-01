# PLANO DO PROJETO: HTML/CSS/JS

> Gerado automaticamente pelo SK Code Editor em 01/10/2026, 06:58:06
> **966 arquivo(s)** | **~109.937 linhas de codigo**

---

## RESUMO EXECUTIVO

- **Tipo de aplicacao:** Aplicacao Web Frontend (React)
- **Frontend / Stack principal:** React, TypeScript

**Para rodar o projeto:**
```bash
# Abra index.html no Preview (botao Play)
```

---

## ESTRUTURA DE ARQUIVOS

```
HTML/CSS/JS/
├── apk-builder/
│   ├── .replit-artifact/
│   │   └── artifact.toml
│   ├── dist/
│   │   └── public/
│   │       ├── assets/
│   │       │   ├── addon-fit-DX4qG4td.js
│   │       │   ├── addon-web-links-DIbG5aQx.js
│   │       │   ├── index-BayuCH0U.js
│   │       │   ├── index-DuH2u_vm.css
│   │       │   ├── xterm-B-qIQCd3.js
│   │       │   └── XTermConnector-DkvdoLSY.js
│   │       ├── assistente-juridico-pwa.zip
│   │       ├── favicon.svg
│   │       ├── icon-192.png
│   │       ├── icon-192.svg
│   │       ├── icon-512.png
│   │       ├── icon-512.svg
│   │       ├── index.html
│   │       ├── manifest.json
│   │       ├── opengraph.jpg
│   │       └── sw.js
│   ├── public/
│   │   ├── favicon.svg
│   │   ├── icon-192.png
│   │   ├── icon-192.svg
│   │   ├── icon-512.png
│   │   ├── icon-512.svg
│   │   ├── manifest.json
│   │   ├── opengraph.jpg
│   │   └── sw.js
│   ├── src/
│   │   ├── components/
│   │   │   ├── ui/
│   │   │   │   ├── accordion.tsx
│   │   │   │   ├── alert-dialog.tsx
│   │   │   │   ├── alert.tsx
│   │   │   │   ├── aspect-ratio.tsx
│   │   │   │   ├── avatar.tsx
│   │   │   │   ├── badge.tsx
│   │   │   │   ├── breadcrumb.tsx
│   │   │   │   ├── button-group.tsx
│   │   │   │   ├── button.tsx
│   │   │   │   ├── calendar.tsx
│   │   │   │   ├── card.tsx
│   │   │   │   ├── carousel.tsx
│   │   │   │   ├── chart.tsx
│   │   │   │   ├── checkbox.tsx
│   │   │   │   ├── collapsible.tsx
│   │   │   │   ├── command.tsx
│   │   │   │   ├── context-menu.tsx
│   │   │   │   ├── dialog.tsx
│   │   │   │   ├── drawer.tsx
│   │   │   │   ├── dropdown-menu.tsx
│   │   │   │   ├── empty.tsx
│   │   │   │   ├── field.tsx
│   │   │   │   ├── form.tsx
│   │   │   │   ├── hover-card.tsx
│   │   │   │   ├── input-group.tsx
│   │   │   │   ├── input-otp.tsx
│   │   │   │   ├── input.tsx
│   │   │   │   ├── item.tsx
│   │   │   │   ├── kbd.tsx
│   │   │   │   ├── label.tsx
│   │   │   │   ├── menubar.tsx
│   │   │   │   ├── navigation-menu.tsx
│   │   │   │   ├── pagination.tsx
│   │   │   │   ├── popover.tsx
│   │   │   │   ├── progress.tsx
│   │   │   │   ├── radio-group.tsx
│   │   │   │   ├── resizable.tsx
│   │   │   │   ├── scroll-area.tsx
│   │   │   │   ├── select.tsx
│   │   │   │   ├── separator.tsx
│   │   │   │   ├── sheet.tsx
│   │   │   │   ├── sidebar.tsx
│   │   │   │   ├── skeleton.tsx
│   │   │   │   ├── slider.tsx
│   │   │   │   ├── sonner.tsx
│   │   │   │   ├── spinner.tsx
│   │   │   │   ├── switch.tsx
│   │   │   │   ├── table.tsx
│   │   │   │   ├── tabs.tsx
│   │   │   │   ├── textarea.tsx
│   │   │   │   ├── toast.tsx
│   │   │   │   ├── toaster.tsx
│   │   │   │   ├── toggle-group.tsx
│   │   │   │   ├── toggle.tsx
│   │   │   │   └── tooltip.tsx
│   │   │   ├── ApkAnalyzer.tsx
│   │   │   ├── TerminalTab.tsx
│   │   │   └── XTermConnector.tsx
│   │   ├── hooks/
│   │   │   ├── use-mobile.tsx
│   │   │   └── use-toast.ts
│   │   ├── lib/
│   │   │   ├── android.ts
│   │   │   ├── archive.ts
│   │   │   ├── github.ts
│   │   │   ├── storage.ts
│   │   │   └── utils.ts
│   │   ├── pages/
│   │   │   └── not-found.tsx
│   │   ├── App.tsx
│   │   ├── index.css
│   │   └── main.tsx
│   ├── components.json
│   ├── index.html
│   ├── package.json
│   ├── tsconfig.json
│   └── vite.config.ts
├── assistente-juridico/
│   ├── android/
│   │   ├── .gradle/
│   │   │   ├── 8.14.3/
│   │   │   │   ├── checksums/
│   │   │   │   │   ├── checksums.lock
│   │   │   │   │   ├── md5-checksums.bin
│   │   │   │   │   └── sha1-checksums.bin
│   │   │   │   ├── executionHistory/
│   │   │   │   │   ├── executionHistory.bin
│   │   │   │   │   └── executionHistory.lock
│   │   │   │   ├── fileChanges/
│   │   │   │   │   └── last-build.bin
│   │   │   │   ├── fileHashes/
│   │   │   │   │   ├── fileHashes.bin
│   │   │   │   │   ├── fileHashes.lock
│   │   │   │   │   └── resourceHashesCache.bin
│   │   │   │   └── gc.properties
│   │   │   ├── buildOutputCleanup/
│   │   │   │   ├── buildOutputCleanup.lock
│   │   │   │   ├── cache.properties
│   │   │   │   └── outputFiles.bin
│   │   │   └── vcs-1/
│   │   │       └── gc.properties
│   │   ├── app/
│   │   │   └── src/
│   │   │       └── main/
│   │   │           ├── assets/
│   │   │           │   ├── public/
│   │   │           │   │   ├── assets/
│   │   │           │   │   │   ├── admin-wZRLZyDy.js
│   │   │           │   │   │   ├── arrow-left-DYElIYXR.js
│   │   │           │   │   │   ├── assinatura-BHt3Qvse.js
│   │   │           │   │   │   ├── auditoria-financeira-C-CiXcAZ.js
│   │   │           │   │   │   ├── badge-BCXvIIul.js
│   │   │           │   │   │   ├── bell-B5W5rjOr.js
│   │   │           │   │   │   ├── book-open-CctBA1uj.js
│   │   │           │   │   │   ├── bot-B-04Xe7b.js
│   │   │           │   │   │   ├── briefcase-jFpqll2q.js
│   │   │           │   │   │   ├── building-2-ywDJkoHl.js
│   │   │           │   │   │   ├── button-D5ZhSwEd.js
│   │   │           │   │   │   ├── calendar-B664tU9C.js
│   │   │           │   │   │   ├── card-BtrX4egs.js
│   │   │           │   │   │   ├── check-CwxI4-xR.js
│   │   │           │   │   │   ├── chevron-down-uth5WLjM.js
│   │   │           │   │   │   ├── chevron-left-BRbXarL_.js
│   │   │           │   │   │   ├── chevron-right-CedePU1E.js
│   │   │           │   │   │   ├── chevron-up-C9iGwLbl.js
│   │   │           │   │   │   ├── circle-alert-DPHqLNmk.js
│   │   │           │   │   │   ├── circle-CG12gPnc.js
│   │   │           │   │   │   ├── circle-x-CwgzW83o.js
│   │   │           │   │   │   ├── clock-D9M-tegz.js
│   │   │           │   │   │   ├── codigo-CFUnhIfo.js
│   │   │           │   │   │   ├── colaborativo-COD6aFte.js
│   │   │           │   │   │   ├── comparador-juridico-DYsbk112.js
│   │   │           │   │   │   ├── comunicacoes-cnj-CJy6IPR8.js
│   │   │           │   │   │   ├── configuracoes-BuhDceYz.js
│   │   │           │   │   │   ├── consulta-corporativo-BSKcbntC.js
│   │   │           │   │   │   ├── consulta-pdpj-BtJMr5YB.js
│   │   │           │   │   │   ├── consulta-processual-CS_HcDnj.js
│   │   │           │   │   │   ├── copy-C0ymX2fa.js
│   │   │           │   │   │   ├── cpu-z3we3BDw.js
│   │   │           │   │   │   ├── database-CYrcrLbK.js
│   │   │           │   │   │   ├── dialog-pO5amdj9.js
│   │   │           │   │   │   ├── download-Bh_vkCgZ.js
│   │   │           │   │   │   ├── ementas-BV15v3HA.js
│   │   │           │   │   │   ├── escritorio-Cl6tGFhQ.js
│   │   │           │   │   │   ├── external-link-caavnAX0.js
│   │   │           │   │   │   ├── eye-DTa4_77d.js
│   │   │           │   │   │   ├── eye-off-BWv1vOKf.js
│   │   │           │   │   │   ├── file-text-D5YgGlaO.js
│   │   │           │   │   │   ├── filtrador-DXCOB_33.js
│   │   │           │   │   │   ├── gavel-Dwyyfr6c.js
│   │   │           │   │   │   ├── hash-CyyXtJxx.js
│   │   │           │   │   │   ├── historico-DDNTQq-I.js
│   │   │           │   │   │   ├── history-B2Xyd_MK.js
│   │   │           │   │   │   ├── index-B-KQ3WUI.js
│   │   │           │   │   │   ├── index-BdQq_4o_.js
│   │   │           │   │   │   ├── index-CkZBBUpY.js
│   │   │           │   │   │   ├── index-CrvuR9uT.css
│   │   │           │   │   │   ├── index-DtqVP6cJ.js
│   │   │           │   │   │   ├── index-hoeJRIQI.js
│   │   │           │   │   │   ├── index-JNL3C0-P.js
│   │   │           │   │   │   ├── index-q_gTu9nj.js
│   │   │           │   │   │   ├── info-xwiNh27h.js
│   │   │           │   │   │   ├── input-BHYEJHxF.js
│   │   │           │   │   │   ├── jurisprudencia-DjNf63tD.js
│   │   │           │   │   │   ├── key-H8121w75.js
│   │   │           │   │   │   ├── label-DDbKw7aq.js
│   │   │           │   │   │   ├── legal-assistant-D8LNF6jM.js
│   │   │           │   │   │   ├── log-out-DcuqR1HY.js
│   │   │           │   │   │   ├── login-D--OVM-N.js
│   │   │           │   │   │   ├── mail-UeVcz8dw.js
│   │   │           │   │   │   ├── message-square-D63Lcg41.js
│   │   │           │   │   │   ├── not-found-BtLd1pRQ.js
│   │   │           │   │   │   ├── painel-processos-Dx2B6hBz.js
│   │   │           │   │   │   ├── pdf-D-oSvAqu.js
│   │   │           │   │   │   ├── pencil-DFfVmNKN.js
│   │   │           │   │   │   ├── pje-BtNTwcaD.js
│   │   │           │   │   │   ├── play-Dmy3Tr5S.js
│   │   │           │   │   │   ├── playground-CiFjVRYw.js
│   │   │           │   │   │   ├── plus-CHNfvhce.js
│   │   │           │   │   │   ├── prazos-BiyhxebU.js
│   │   │           │   │   │   ├── previdenciario-BgZf2Tbb.js
│   │   │           │   │   │   ├── refresh-cw-CUZ4KEwd.js
│   │   │           │   │   │   ├── robo-djen-cJK4ep0K.js
│   │   │           │   │   │   ├── rotate-ccw-BuKmPR_P.js
│   │   │           │   │   │   ├── save-C8RRHb15.js
│   │   │           │   │   │   ├── scale-GBhUYU-E.js
│   │   │           │   │   │   ├── search-jJ27H8hL.js
│   │   │           │   │   │   ├── select-DDIifz52.js
│   │   │           │   │   │   ├── separator-Dfm4ZYD4.js
│   │   │           │   │   │   ├── server-MMXj2nPg.js
│   │   │           │   │   │   ├── settings-D81hJRVO.js
│   │   │           │   │   │   ├── shield-DrACl4xC.js
│   │   │           │   │   │   ├── slider-CZPfl0zr.js
│   │   │           │   │   │   ├── status-CLTSdRTB.js
│   │   │           │   │   │   ├── tabs-C8YWXfKh.js
│   │   │           │   │   │   ├── tag-CzW8KDkR.js
│   │   │           │   │   │   ├── target-D1gUxVkr.js
│   │   │           │   │   │   ├── templates-juridicos-nosr4NEB.js
│   │   │           │   │   │   ├── terminal-jLiJtK1h.js
│   │   │           │   │   │   ├── textarea-CCtB2qGH.js
│   │   │           │   │   │   ├── theme-toggle-Dbf3_SAN.js
│   │   │           │   │   │   ├── tiptap-editor-Df4ueogS.js
│   │   │           │   │   │   ├── token-generator-vOUVwjyA.js
│   │   │           │   │   │   ├── tramitacao-8LC-yeQF.js
│   │   │           │   │   │   ├── trash-2-Mk5MkyoA.js
│   │   │           │   │   │   ├── triangle-alert-v4TJhy5N.js
│   │   │           │   │   │   ├── upload-D1eWvUVm.js
│   │   │           │   │   │   ├── useMutation-BW5OEpvQ.js
│   │   │           │   │   │   ├── user-check-CJpgpIJk.js
│   │   │           │   │   │   ├── user-JeTrnZj0.js
│   │   │           │   │   │   ├── users-BVC16TKt.js
│   │   │           │   │   │   ├── volume-x-B8490iQ3.js
│   │   │           │   │   │   ├── wifi-off-B1XPEx6z.js
│   │   │           │   │   │   └── zap-DuTIlcWP.js
│   │   │           │   │   ├── cordova_plugins.js
│   │   │           │   │   ├── cordova.js
│   │   │           │   │   ├── favicon.svg
│   │   │           │   │   ├── icon-192.png
│   │   │           │   │   ├── icon-384.png
│   │   │           │   │   ├── icon-512.png
│   │   │           │   │   ├── icon-96.png
│   │   │           │   │   ├── index.html
│   │   │           │   │   ├── manifest.json
│   │   │           │   │   ├── opengraph.jpg
│   │   │           │   │   ├── robots.txt
│   │   │           │   │   ├── SK-Juridico-IA.apk
│   │   │           │   │   └── sw.js
│   │   │           │   ├── capacitor.config.json
│   │   │           │   └── capacitor.plugins.json
│   │   │           └── res/
│   │   │               └── xml/
│   │   │                   └── config.xml
│   │   ├── capacitor-cordova-android-plugins/
│   │   │   ├── src/
│   │   │   │   └── main/
│   │   │   │       ├── java/
│   │   │   │       │   └── .gitkeep
│   │   │   │       ├── res/
│   │   │   │       │   └── .gitkeep
│   │   │   │       └── AndroidManifest.xml
│   │   │   ├── build.gradle
│   │   │   └── cordova.variables.gradle
│   │   └── local.properties
│   └── dist/
│       ├── assets/
│       │   ├── admin-DdVWhbJZ.js
│       │   ├── arrow-left-nBCyQW32.js
│       │   ├── assinatura-DhMNHOKB.js
│       │   ├── badge-CeQ9YgHg.js
│       │   ├── bell-S8SoMvhJ.js
│       │   ├── book-open-jGqVCAaa.js
│       │   ├── bot-BPZdrzKs.js
│       │   ├── briefcase-JIjjIAIQ.js
│       │   ├── building-2-DuXwQ01A.js
│       │   ├── button-DogYNL8m.js
│       │   ├── calendar-C8eS9BJ3.js
│       │   ├── card-CAMPMs4I.js
│       │   ├── check-Cw4MhVxd.js
│       │   ├── chevron-down-CSLxLrLQ.js
│       │   ├── chevron-left-D8dWNoIe.js
│       │   ├── chevron-right-QUxraXO5.js
│       │   ├── chevron-up-B-NrD1Yf.js
│       │   ├── circle-alert-CODgC0Wt.js
│       │   ├── circle-check-BvyNknoB.js
│       │   ├── circle-CpSIygtO.js
│       │   ├── circle-x-BI8lMh8t.js
│       │   ├── clock-Cp3l2mis.js
│       │   ├── codigo-CBvzBZYN.js
│       │   ├── colaborativo-Bmjhl7Bs.js
│       │   ├── comparador-juridico-e11bTEP1.js
│       │   ├── comunicacoes-cnj-DF3LmGtR.js
│       │   ├── configuracoes-DyhSBsZW.js
│       │   ├── consulta-corporativo-AH19UW8F.js
│       │   ├── consulta-pdpj-CmwGfWNe.js
│       │   ├── consulta-processual-DT9PR3AD.js
│       │   ├── copy-BJbuHhiB.js
│       │   ├── cpu-H9bqy-ol.js
│       │   ├── database-DPXDRvNh.js
│       │   ├── dialog-BW4Lb6A6.js
│       │   ├── download-CYbqGIYu.js
│       │   ├── ementas-GuvS-wAN.js
│       │   ├── escritorio-D5Xc-ipL.js
│       │   ├── external-link-CEf6uMDg.js
│       │   ├── eye-NEq-3FD4.js
│       │   ├── eye-off-BkyV4iqA.js
│       │   ├── file-text-CVJYXn7I.js
│       │   ├── filtrador-Uh5o5CGF.js
│       │   ├── gavel-7xOSQuEL.js
│       │   ├── globe-DqXCJqaQ.js
│       │   ├── hash-DXrFETIG.js
│       │   ├── historico-BHc_45HR.js
│       │   ├── history-Dm5s-98n.js
│       │   ├── index-B-_-zVh9.js
│       │   ├── index-BdQq_4o_.js
│       │   ├── index-Cajry1w2.js
│       │   ├── index-DGVWKFBB.js
│       │   ├── index-Dha_x3eW.js
│       │   ├── index-Do0OOi2v.css
│       │   ├── index-Dt5FInq3.js
│       │   ├── index-ZJT4jjP1.js
│       │   ├── info-Bv65dD_K.js
│       │   ├── input-BsVrziBy.js
│       │   ├── jurisprudencia-OuGxXOY4.js
│       │   ├── key-Ba8qnwem.js
│       │   ├── label-Cc5cm9uG.js
│       │   ├── legal-assistant-v7qssgXW.js
│       │   ├── log-out-C1v4nIPP.js
│       │   ├── login-7hMOiJ2J.js
│       │   ├── mail-DIZQZj_s.js
│       │   ├── message-square-D_Z2gJKw.js
│       │   ├── not-found-DSZWET4-.js
│       │   ├── painel-processos-B7i2NMof.js
│       │   ├── pdf-B75MOh95.js
│       │   ├── pencil-Q_CBYcqn.js
│       │   ├── pje-9CSE9fDi.js
│       │   ├── play-DfmtkRyB.js
│       │   ├── playground-DD29hz3O.js
│       │   ├── plus-DfNIQMpt.js
│       │   ├── prazos-DF6K-tvm.js
│       │   ├── previdenciario-DkaB0ujZ.js
│       │   ├── refresh-cw-D5__vk8G.js
│       │   ├── robo-djen-D3WPdr0u.js
│       │   ├── rotate-ccw-D28OuoVq.js
│       │   ├── save-BnF37M3_.js
│       │   ├── scale-i6eM2OQ9.js
│       │   ├── search-B1p4_U_k.js
│       │   ├── select-DutfNDZp.js
│       │   ├── separator-DQXp5lNG.js
│       │   ├── server-DNeVClqP.js
│       │   ├── settings-Cudh-Mnh.js
│       │   ├── shield-CeeBT9p1.js
│       │   ├── slider-D0R0PB6j.js
│       │   ├── status-B5oxDYuU.js
│       │   ├── tabs-DnoBjg6K.js
│       │   ├── tag-B3no2Wh0.js
│       │   ├── target-BCM4Kr-t.js
│       │   ├── templates-juridicos-1Iq21zIV.js
│       │   ├── terminal-BajxkcBh.js
│       │   ├── textarea-CDo_t3Pz.js
│       │   ├── theme-toggle-DD5PSROF.js
│       │   ├── tiptap-editor-DxlsD-7E.js
│       │   ├── token-generator-OcTrrzh7.js
│       │   ├── tramitacao-BxlsSwUG.js
│       │   ├── trash-2-DDvNxfXN.js
│       │   ├── triangle-alert-DSonC7Kt.js
│       │   ├── upload-Bl3wdvk6.js
│       │   ├── useMutation-DjoeqaNn.js
│       │   ├── user-7yy-BCdS.js
│       │   ├── user-check-vp_bBrF6.js
│       │   ├── users-DONy9nTq.js
│       │   ├── volume-x-DcwW5KKL.js
│       │   ├── wifi-B6Kj2hWi.js
│       │   └── zap-uo4Z6IN6.js
│       ├── public/
│       │   ├── assets/
│       │   │   ├── admin-CBkE_xRa.js
│       │   │   ├── arrow-left-De2M_wPP.js
│       │   │   ├── assinatura-BxGVlQr8.js
│       │   │   ├── badge-DvsEBxZE.js
│       │   │   ├── bell-BAx4uqwM.js
│       │   │   ├── book-open-C60h3AJh.js
│       │   │   ├── bot-CQEA4oRY.js
│       │   │   ├── building-2-BXpbgOaa.js
│       │   │   ├── button-BUGwJ1r4.js
│       │   │   ├── calendar-Bn-2Hr63.js
│       │   │   ├── card-mbB_popU.js
│       │   │   ├── check-efW8jyn0.js
│       │   │   ├── chevron-down-r3_9_CMA.js
│       │   │   ├── chevron-left-BLKLetW2.js
│       │   │   ├── chevron-right-BzsbPMa4.js
│       │   │   ├── chevron-up-KuwEdWNQ.js
│       │   │   ├── circle-alert-eSv2vETe.js
│       │   │   ├── circle-check-B6Hbs4xE.js
│       │   │   ├── circle-DjYp1w7I.js
│       │   │   ├── circle-x-gjVK4Jgn.js
│       │   │   ├── clock-C4R428W7.js
│       │   │   ├── codigo-DICocSqs.js
│       │   │   ├── colaborativo-CCSq-6n3.js
│       │   │   ├── comparador-juridico-349a-1z6.js
│       │   │   ├── comunicacoes-cnj-Bz91U-FP.js
│       │   │   ├── configuracoes-Ct8H_2FW.js
│       │   │   ├── consulta-corporativo-DM1UUrc5.js
│       │   │   ├── consulta-pdpj-3DTOMKnM.js
│       │   │   ├── consulta-processual-Cw2Gu7NA.js
│       │   │   ├── copy-BFLCPv5x.js
│       │   │   ├── cpu-C024Qcuy.js
│       │   │   ├── database-DLAbLVck.js
│       │   │   ├── dialog-BAg_0Wok.js
│       │   │   ├── download-DuwWgM3Q.js
│       │   │   ├── ementas-CJZty0Wh.js
│       │   │   ├── escritorio-BLm-INPe.js
│       │   │   ├── external-link-BxUuqUaE.js
│       │   │   ├── eye-GP31qHS-.js
│       │   │   ├── eye-off-CnZx4Rv_.js
│       │   │   ├── file-text-Bv5C0iRI.js
│       │   │   ├── filtrador-ChgRMOq6.js
│       │   │   ├── gavel-BJpPYw1K.js
│       │   │   ├── historico-oQEcg4nM.js
│       │   │   ├── history-2mjGnPtq.js
│       │   │   ├── index-39mgIYgx.js
│       │   │   ├── index-AUXLjOsf.js
│       │   │   ├── index-BdQq_4o_.js
│       │   │   ├── index-BVE5xndR.js
│       │   │   ├── index-Dju8vJgD.js
│       │   │   ├── index-DOpuvYws.css
│       │   │   ├── index-DOQDzLwe.js
│       │   │   ├── index-MfVsal_x.js
│       │   │   ├── info-CTTXh9QD.js
│       │   │   ├── input-LSRw2cwy.js
│       │   │   ├── jurisprudencia-B2y-dTXc.js
│       │   │   ├── key-BBkVXwEW.js
│       │   │   ├── label-OX8Mn1-0.js
│       │   │   ├── legal-assistant-A7mZ5Kt6.js
│       │   │   ├── log-out-Bw9EOYRA.js
│       │   │   ├── login-Dzsw5OEx.js
│       │   │   ├── mail-BNiJ5jWe.js
│       │   │   ├── message-square-0jM2-GKg.js
│       │   │   ├── not-found-Dpb2K0qk.js
│       │   │   ├── painel-processos-CcOi2au5.js
│       │   │   ├── pdf-B75MOh95.js
│       │   │   ├── pencil-DBnBVZSc.js
│       │   │   ├── pje-mlPLPa45.js
│       │   │   ├── play-Dk83ynRF.js
│       │   │   ├── playground-CZrotIxo.js
│       │   │   ├── plus-Du7Lo3bz.js
│       │   │   ├── prazos-Pg0PZw65.js
│       │   │   ├── refresh-cw-GPND3eQm.js
│       │   │   ├── robo-djen-Ix2S-0G6.js
│       │   │   ├── rotate-ccw-Cg5i5ug3.js
│       │   │   ├── save-DOpTQH4r.js
│       │   │   ├── scale-BfcSY8rh.js
│       │   │   ├── search-rmZIdwX6.js
│       │   │   ├── select-Bnqk4twF.js
│       │   │   ├── separator-D_rvx2CS.js
│       │   │   ├── server-DbDCGMHt.js
│       │   │   ├── settings-BCCdn6tP.js
│       │   │   ├── shield-BaXcWJi9.js
│       │   │   ├── slider-CiGH8XhB.js
│       │   │   ├── status-CQbd-8UQ.js
│       │   │   ├── tabs-BgH_zz7Z.js
│       │   │   ├── tag-BHLeQaPL.js
│       │   │   ├── target-BD3QZD5M.js
│       │   │   ├── templates-juridicos-1ZiNvz08.js
│       │   │   ├── terminal-DjCaBnXe.js
│       │   │   ├── textarea-CW5o07-G.js
│       │   │   ├── theme-toggle-DxQ7IR8r.js
│       │   │   ├── tiptap-editor-CMlHrtsu.js
│       │   │   ├── token-generator-BGC3zoEJ.js
│       │   │   ├── tramitacao-DsUHMM8Q.js
│       │   │   ├── trash-2-DEBfAqIY.js
│       │   │   ├── triangle-alert-B4YV2-Gk.js
│       │   │   ├── upload-Cj7-ngfC.js
│       │   │   ├── useMutation-BJ86liox.js
│       │   │   ├── user-B9hczYUr.js
│       │   │   ├── user-check-DrvS6C4f.js
│       │   │   ├── users-DB2QB59g.js
│       │   │   ├── volume-x-CTBNzjlm.js
│       │   │   ├── wifi-off-CbHSy9GE.js
│       │   │   └── zap-B2kCwK0T.js
│       │   ├── favicon.svg
│       │   ├── icon-192.png
│       │   ├── icon-384.png
│       │   ├── icon-512.png
│       │   ├── icon-96.png
│       │   ├── index.html
│       │   ├── manifest.json
│       │   ├── opengraph.jpg
│       │   ├── robots.txt
│       │   ├── setup-preview.html
│       │   ├── SK-Juridico-IA-v1.8.apk
│       │   ├── SK-Juridico-IA.apk
│       │   └── sw.js
│       ├── cordova_plugins.js
│       ├── cordova.js
│       ├── favicon.svg
│       ├── icon-192.png
│       ├── icon-384.png
│       ├── icon-512.png
│       ├── icon-96.png
│       ├── index.html
│       ├── manifest.json
│       ├── opengraph.jpg
│       ├── robots.txt
│       └── sw.js
├── juridico/
│   ├── .replit-artifact/
│   │   └── artifact.toml
│   ├── dist/
│   │   └── public/
│   │       ├── assets/
│   │       │   ├── admin-CSYibXzg.js
│   │       │   ├── arrow-left-DBwtgAcy.js
│   │       │   ├── assinatura-CpoFU8iN.js
│   │       │   ├── audio-lines-DsBMIcUK.js
│   │       │   ├── auditoria-financeira-BTiZ_MnQ.js
│   │       │   ├── badge-CD7rZS7n.js
│   │       │   ├── bell-Cht0EACw.js
│   │       │   ├── book-open-BKWsciMp.js
│   │       │   ├── bot-CpPmyCuP.js
│   │       │   ├── briefcase-B5MNLBsd.js
│   │       │   ├── building-2-CEkB_bNa.js
│   │       │   ├── button-DmWEFtXm.js
│   │       │   ├── calendar-wAE2F37_.js
│   │       │   ├── card-BipkLjeB.js
│   │       │   ├── check-BnLyF3Wu.js
│   │       │   ├── chevron-down-C8pb4oN1.js
│   │       │   ├── chevron-left-CCCXiGGa.js
│   │       │   ├── chevron-right-D1ryeHHM.js
│   │       │   ├── chevron-up-Cge-G70_.js
│   │       │   ├── circle-alert-nMBd91WP.js
│   │       │   ├── circle-BASCHiMY.js
│   │       │   ├── circle-check-CM4Qdbnm.js
│   │       │   ├── circle-stop-C2ikIssX.js
│   │       │   ├── circle-x-qu7znTBo.js
│   │       │   ├── clock-BbEb8j2V.js
│   │       │   ├── codigo-CcBp48WS.js
│   │       │   ├── colaborativo-D6VQuPIO.js
│   │       │   ├── comparador-juridico-Cliqnr15.js
│   │       │   ├── comunicacoes-cnj-BeEOY83h.js
│   │       │   ├── configuracoes-BSFwYNAK.js
│   │       │   ├── consulta-corporativo-BWNqd6Yg.js
│   │       │   ├── consulta-pdpj-CF1e66rQ.js
│   │       │   ├── consulta-processual-DDmG4iSv.js
│   │       │   ├── copy-C7yzOVrI.js
│   │       │   ├── cpu-BYm_2wvI.js
│   │       │   ├── database-Dllzk6br.js
│   │       │   ├── dialog-C_UTeQ-Z.js
│   │       │   ├── download-DnUulWCg.js
│   │       │   ├── ementas-AisZ7hh-.js
│   │       │   ├── escritorio-DlPQALZe.js
│   │       │   ├── external-link-BgiAxW7g.js
│   │       │   ├── eye-off-DNQQfmQu.js
│   │       │   ├── eye-sSfRAZ3B.js
│   │       │   ├── file-text-DeLlVhKq.js
│   │       │   ├── fileExtract-DHdlQI-A.js
│   │       │   ├── filtrador-cyiDAYMn.js
│   │       │   ├── folder-open-Hodf7wN5.js
│   │       │   ├── gavel-B06xpq47.js
│   │       │   ├── globe-DuhDY7M0.js
│   │       │   ├── guia-C7Wlu1qL.js
│   │       │   ├── hash-Bw4xy2Sx.js
│   │       │   ├── historico-CLCC7I0D.js
│   │       │   ├── history-ByeCVPNp.js
│   │       │   ├── iara-Bd1pWhht.js
│   │       │   ├── index-_XSsFKKV.js
│   │       │   ├── index-28kpihTt.js
│   │       │   ├── index-B0YTb96v.js
│   │       │   ├── index-BdQq_4o_.js
│   │       │   ├── index-C024M3US.js
│   │       │   ├── index-CV6QfelB.css
│   │       │   ├── index-CyxGmtCR.js
│   │       │   ├── index-odkcds6s.js
│   │       │   ├── info-C5AUWl9g.js
│   │       │   ├── input-Beq58fdb.js
│   │       │   ├── juridico-pro-BWCnCh2d.js
│   │       │   ├── jurisprudencia-DvzR4k6L.js
│   │       │   ├── key-CTaoIv58.js
│   │       │   ├── label-HELNMd2g.js
│   │       │   ├── legal-assistant-7f5CZd36.js
│   │       │   ├── log-out-BeBgRdd1.js
│   │       │   ├── login-CE_5BhYm.js
│   │       │   ├── mail-BPCTbTIi.js
│   │       │   ├── message-square-BIdD7JRM.js
│   │       │   ├── not-found-GHY-j2Fl.js
│   │       │   ├── painel-processos-e5eYYiY3.js
│   │       │   ├── pdf-B75MOh95.js
│   │       │   ├── pencil-h4X763Lf.js
│   │       │   ├── pje-0rVw9OtK.js
│   │       │   ├── play-LyUojDBq.js
│   │       │   ├── playground-C0OXxrnU.js
│   │       │   ├── plus-CD9lH7pR.js
│   │       │   ├── prazos-Ca2drPlS.js
│   │       │   ├── previdenciario-CHmA8mVg.js
│   │       │   ├── refresh-cw-DLZ40eiX.js
│   │       │   ├── robo-djen-DaDoUMvg.js
│   │       │   ├── rotate-ccw-BDKSv7NN.js
│   │       │   ├── save-BtYt8O-3.js
│   │       │   ├── scale-DL44_Z-P.js
│   │       │   ├── search-CUEuJlJo.js
│   │       │   ├── select-BaIKZQjg.js
│   │       │   ├── separator-K4xwL5Pb.js
│   │       │   ├── server-YwLnhmJu.js
│   │       │   ├── settings-CdQsakcp.js
│   │       │   ├── shield-vDD54pHO.js
│   │       │   ├── slider-Dzf2vR38.js
│   │       │   ├── status--LNis53d.js
│   │       │   ├── tabs-Bxm6G3dy.js
│   │       │   ├── tag-LbJW7TIK.js
│   │       │   ├── target-BZCQz0Bh.js
│   │       │   ├── templates-juridicos-Cwfg0dU9.js
│   │       │   ├── terminal-BUZM54jF.js
│   │       │   ├── textarea-_aV9rgWP.js
│   │       │   ├── theme-toggle-BCfIU4lM.js
│   │       │   ├── tiptap-editor-BJcziLjr.js
│   │       │   ├── token-generator-ZC4hDR0T.js
│   │       │   ├── tramitacao-Mzn2xBf9.js
│   │       │   ├── trash-2-Cy2W2HFq.js
│   │       │   ├── triangle-alert-DOLme-hg.js
│   │       │   ├── upload-Mpfhr3q3.js
│   │       │   ├── useMutation-CYMlB8dT.js
│   │       │   ├── user-A83hgMSo.js
│   │       │   ├── user-check-KjU15eFV.js
│   │       │   ├── users-Do3AZQrD.js
│   │       │   ├── volume-2-Bp1t5cX0.js
│   │       │   ├── volume-x-DAyhgBMg.js
│   │       │   ├── wifi-BFhgqE2o.js
│   │       │   └── zap-CyosTu31.js
│   │       ├── icons/
│   │       │   ├── icon-128x128.svg
│   │       │   ├── icon-144x144.svg
│   │       │   ├── icon-152x152.svg
│   │       │   ├── icon-192x192.svg
│   │       │   ├── icon-384x384.svg
│   │       │   ├── icon-512x512.svg
│   │       │   ├── icon-72x72.svg
│   │       │   └── icon-96x96.svg
│   │       ├── favicon.svg
│   │       ├── index.html
│   │       ├── manifest.webmanifest
│   │       ├── opengraph.jpg
│   │       ├── registerSW.js
│   │       ├── robots.txt
│   │       ├── sw.js
│   │       └── workbox-6829fd8d.js
│   ├── public/
│   │   ├── icons/
│   │   │   ├── icon-128x128.svg
│   │   │   ├── icon-144x144.svg
│   │   │   ├── icon-152x152.svg
│   │   │   ├── icon-192x192.svg
│   │   │   ├── icon-384x384.svg
│   │   │   ├── icon-512x512.svg
│   │   │   ├── icon-72x72.svg
│   │   │   └── icon-96x96.svg
│   │   ├── favicon.svg
│   │   ├── opengraph.jpg
│   │   └── robots.txt
│   ├── src/
│   │   ├── components/
│   │   │   ├── ui/
│   │   │   │   ├── accordion.tsx
│   │   │   │   ├── alert-dialog.tsx
│   │   │   │   ├── alert.tsx
│   │   │   │   ├── aspect-ratio.tsx
│   │   │   │   ├── avatar.tsx
│   │   │   │   ├── badge.tsx
│   │   │   │   ├── breadcrumb.tsx
│   │   │   │   ├── button-group.tsx
│   │   │   │   ├── button.tsx
│   │   │   │   ├── calendar.tsx
│   │   │   │   ├── card.tsx
│   │   │   │   ├── carousel.tsx
│   │   │   │   ├── chart.tsx
│   │   │   │   ├── checkbox.tsx
│   │   │   │   ├── collapsible.tsx
│   │   │   │   ├── command.tsx
│   │   │   │   ├── context-menu.tsx
│   │   │   │   ├── dialog.tsx
│   │   │   │   ├── drawer.tsx
│   │   │   │   ├── dropdown-menu.tsx
│   │   │   │   ├── empty.tsx
│   │   │   │   ├── field.tsx
│   │   │   │   ├── form.tsx
│   │   │   │   ├── hover-card.tsx
│   │   │   │   ├── input-group.tsx
│   │   │   │   ├── input-otp.tsx
│   │   │   │   ├── input.tsx
│   │   │   │   ├── item.tsx
│   │   │   │   ├── kbd.tsx
│   │   │   │   ├── label.tsx
│   │   │   │   ├── menubar.tsx
│   │   │   │   ├── navigation-menu.tsx
│   │   │   │   ├── pagination.tsx
│   │   │   │   ├── popover.tsx
│   │   │   │   ├── progress.tsx
│   │   │   │   ├── radio-group.tsx
│   │   │   │   ├── resizable.tsx
│   │   │   │   ├── scroll-area.tsx
│   │   │   │   ├── select.tsx
│   │   │   │   ├── separator.tsx
│   │   │   │   ├── sheet.tsx
│   │   │   │   ├── sidebar.tsx
│   │   │   │   ├── skeleton.tsx
│   │   │   │   ├── slider.tsx
│   │   │   │   ├── sonner.tsx
│   │   │   │   ├── spinner.tsx
│   │   │   │   ├── switch.tsx
│   │   │   │   ├── table.tsx
│   │   │   │   ├── tabs.tsx
│   │   │   │   ├── textarea.tsx
│   │   │   │   ├── toast.tsx
│   │   │   │   ├── toaster.tsx
│   │   │   │   ├── toggle-group.tsx
│   │   │   │   ├── toggle.tsx
│   │   │   │   └── tooltip.tsx
│   │   │   ├── Layout.tsx
│   │   │   ├── PinLock.tsx
│   │   │   ├── pwa-install.tsx
│   │   │   ├── theme-provider.tsx
│   │   │   ├── theme-toggle.tsx
│   │   │   └── tiptap-editor.tsx
│   │   ├── hooks/
│   │   │   ├── use-mobile.tsx
│   │   │   ├── use-toast.ts
│   │   │   └── useLocalStorage.ts
│   │   ├── lib/
│   │   │   ├── aiDirect.ts
│   │   │   ├── apiInterceptor.ts
│   │   │   ├── fileExtract.ts
│   │   │   ├── legal-formatter.ts
│   │   │   ├── localDB.ts
│   │   │   ├── queryClient.ts
│   │   │   ├── speech.ts
│   │   │   ├── storage.ts
│   │   │   ├── sync-storage.ts
│   │   │   ├── tts-service.ts
│   │   │   └── utils.ts
│   │   ├── pages/
│   │   │   ├── admin.tsx
│   │   │   ├── assinatura.tsx
│   │   │   ├── Assistente.tsx
│   │   │   ├── Audiencias.tsx
│   │   │   ├── auditoria-financeira.tsx
│   │   │   ├── Clientes.tsx
│   │   │   ├── codigo.tsx
│   │   │   ├── colaborativo.tsx
│   │   │   ├── comparador-juridico.tsx
│   │   │   ├── comunicacoes-cnj.tsx
│   │   │   ├── ComunicacoesProcessuais.tsx
│   │   │   ├── configuracoes.tsx
│   │   │   ├── Configuracoes.tsx
│   │   │   ├── consulta-corporativo.tsx
│   │   │   ├── consulta-pdpj.tsx
│   │   │   ├── consulta-processual.tsx
│   │   │   ├── Dashboard.tsx
│   │   │   ├── Documentos.tsx
│   │   │   ├── ementas.tsx
│   │   │   ├── escritorio.tsx
│   │   │   ├── ExtractorJuridico.tsx
│   │   │   ├── filtrador.tsx
│   │   │   ├── guia.tsx
│   │   │   ├── historico.tsx
│   │   │   ├── HtmlPlayground.tsx
│   │   │   ├── iara.tsx
│   │   │   ├── juridico-pro.tsx
│   │   │   ├── jurisprudencia.tsx
│   │   │   ├── legal-assistant.tsx
│   │   │   ├── login.tsx
│   │   │   ├── not-found.tsx
│   │   │   ├── painel-processos.tsx
│   │   │   ├── pje.tsx
│   │   │   ├── playground.tsx
│   │   │   ├── prazos.tsx
│   │   │   ├── previdenciario.tsx
│   │   │   ├── Processos.tsx
│   │   │   ├── robo-djen.tsx
│   │   │   ├── status.tsx
│   │   │   ├── templates-juridicos.tsx
│   │   │   ├── Templates.tsx
│   │   │   ├── token-generator.tsx
│   │   │   └── tramitacao.tsx
│   │   ├── App.tsx
│   │   ├── index.css
│   │   └── main.tsx
│   ├── components.json
│   ├── index.html
│   ├── package.json
│   ├── tsconfig.json
│   └── vite.config.ts
├── sk-editor/
│   ├── .replit-artifact/
│   │   └── artifact.toml
│   ├── dist/
│   │   └── public/
│   │       ├── assets/
│   │       │   ├── addon-fit-DX4qG4td.js
│   │       │   ├── addon-web-links-DIbG5aQx.js
│   │       │   ├── index-Cg47B_PG.css
│   │       │   ├── index-Dn05cZXz.js
│   │       │   ├── xterm-B-qIQCd3.js
│   │       │   └── XTermConnector-udiVE6cg.js
│   │       ├── favicon.svg
│   │       ├── guia-completo-apk.md
│   │       ├── icon-192.png
│   │       ├── icon-512.png
│   │       ├── index.html
│   │       ├── manifest.json
│   │       ├── manual-dev.md
│   │       ├── MANUAL-SK-CODE-EDITOR.md
│   │       ├── opengraph.jpg
│   │       └── sw.js
│   ├── public/
│   │   ├── favicon.svg
│   │   ├── guia-completo-apk.md
│   │   ├── icon-192.png
│   │   ├── icon-512.png
│   │   ├── manifest.json
│   │   ├── manual-dev.md
│   │   ├── MANUAL-SK-CODE-EDITOR.md
│   │   ├── opengraph.jpg
│   │   └── sw.js
│   ├── src/
│   │   ├── components/
│   │   │   ├── ui/
│   │   │   │   ├── accordion.tsx
│   │   │   │   ├── alert-dialog.tsx
│   │   │   │   ├── alert.tsx
│   │   │   │   ├── aspect-ratio.tsx
│   │   │   │   ├── avatar.tsx
│   │   │   │   ├── badge.tsx
│   │   │   │   ├── breadcrumb.tsx
│   │   │   │   ├── button-group.tsx
│   │   │   │   ├── button.tsx
│   │   │   │   ├── calendar.tsx
│   │   │   │   ├── card.tsx
│   │   │   │   ├── carousel.tsx
│   │   │   │   ├── chart.tsx
│   │   │   │   ├── checkbox.tsx
│   │   │   │   ├── collapsible.tsx
│   │   │   │   ├── command.tsx
│   │   │   │   ├── context-menu.tsx
│   │   │   │   ├── dialog.tsx
│   │   │   │   ├── drawer.tsx
│   │   │   │   ├── dropdown-menu.tsx
│   │   │   │   ├── empty.tsx
│   │   │   │   ├── field.tsx
│   │   │   │   ├── form.tsx
│   │   │   │   ├── hover-card.tsx
│   │   │   │   ├── input-group.tsx
│   │   │   │   ├── input-otp.tsx
│   │   │   │   ├── input.tsx
│   │   │   │   ├── item.tsx
│   │   │   │   ├── kbd.tsx
│   │   │   │   ├── label.tsx
│   │   │   │   ├── menubar.tsx
│   │   │   │   ├── navigation-menu.tsx
│   │   │   │   ├── pagination.tsx
│   │   │   │   ├── popover.tsx
│   │   │   │   ├── progress.tsx
│   │   │   │   ├── radio-group.tsx
│   │   │   │   ├── resizable.tsx
│   │   │   │   ├── scroll-area.tsx
│   │   │   │   ├── select.tsx
│   │   │   │   ├── separator.tsx
│   │   │   │   ├── sheet.tsx
│   │   │   │   ├── sidebar.tsx
│   │   │   │   ├── skeleton.tsx
│   │   │   │   ├── slider.tsx
│   │   │   │   ├── sonner.tsx
│   │   │   │   ├── spinner.tsx
│   │   │   │   ├── switch.tsx
│   │   │   │   ├── table.tsx
│   │   │   │   ├── tabs.tsx
│   │   │   │   ├── textarea.tsx
│   │   │   │   ├── toast.tsx
│   │   │   │   ├── toaster.tsx
│   │   │   │   ├── toggle-group.tsx
│   │   │   │   ├── toggle.tsx
│   │   │   │   └── tooltip.tsx
│   │   │   ├── AIChat.tsx
│   │   │   ├── AssistenteJuridico.tsx
│   │   │   ├── CampoLivre.tsx
│   │   │   ├── CodeEditor.tsx
│   │   │   ├── CombinarApps.tsx
│   │   │   ├── DriveBackupPanel.tsx
│   │   │   ├── EditorLayout.tsx
│   │   │   ├── FileTree.tsx
│   │   │   ├── GitHubPanel.tsx
│   │   │   ├── Manual.tsx
│   │   │   ├── PackageSearch.tsx
│   │   │   ├── Preview.tsx
│   │   │   ├── QuickPrompt.tsx
│   │   │   ├── RealTerminal.tsx
│   │   │   ├── SKTerminal.tsx
│   │   │   ├── StreamTerminal.tsx
│   │   │   ├── SystemStatusPanel.tsx
│   │   │   ├── TemplateSelector.tsx
│   │   │   ├── Terminal.tsx
│   │   │   ├── VoiceCard.tsx
│   │   │   ├── VoiceMode.tsx
│   │   │   ├── WebContainerTerminal.tsx
│   │   │   └── XTermConnector.tsx
│   │   ├── hooks/
│   │   │   ├── use-mobile.tsx
│   │   │   └── use-toast.ts
│   │   ├── lib/
│   │   │   ├── ai-service.ts
│   │   │   ├── github-service.ts
│   │   │   ├── projects.ts
│   │   │   ├── store.ts
│   │   │   ├── templates.ts
│   │   │   ├── tts-service.ts
│   │   │   ├── utils.ts
│   │   │   ├── virtual-fs.ts
│   │   │   └── zip-service.ts
│   │   ├── pedaços de outros/
│   │   │   ├── ai-panel_1778769976970.tsx
│   │   │   ├── preview-panel_1778769880659.tsx
│   │   │   └── settings_1778769824105.tsx
│   │   ├── App.tsx
│   │   ├── index.css
│   │   └── main.tsx
│   ├── components.json
│   ├── index.html
│   ├── package.json
│   ├── SYSTEM_DOCS.md
│   ├── tsconfig.json
│   └── vite.config.ts
└── sk-mobile/
    ├── .expo/
    │   ├── types/
    │   │   └── router.d.ts
    │   ├── web/
    │   │   └── cache/
    │   │       └── production/
    │   │           └── images/
    │   │               ├── android-adaptive-foreground/
    │   │               │   └── android-adaptive-foreground-3b544823f512e77f9b3b3b4b73f1d24f0f05d2d6111352ce92d66c01f0741b9c-cover-transparent/
    │   │               │       ├── icon_108.png
    │   │               │       ├── icon_162.png
    │   │               │       ├── icon_216.png
    │   │               │       ├── icon_324.png
    │   │               │       └── icon_432.png
    │   │               ├── android-standard-square/
    │   │               │   └── android-standard-square-3b544823f512e77f9b3b3b4b73f1d24f0f05d2d6111352ce92d66c01f0741b9c-cover-transparent/
    │   │               │       ├── icon_144.png
    │   │               │       ├── icon_192.png
    │   │               │       ├── icon_48.png
    │   │               │       ├── icon_72.png
    │   │               │       └── icon_96.png
    │   │               ├── favicon/
    │   │               │   └── favicon-3b544823f512e77f9b3b3b4b73f1d24f0f05d2d6111352ce92d66c01f0741b9c-contain-transparent/
    │   │               │       └── favicon-48.png
    │   │               └── splash-android/
    │   │                   └── splash-android-3b544823f512e77f9b3b3b4b73f1d24f0f05d2d6111352ce92d66c01f0741b9c-contain/
    │   │                       ├── icon_200.png
    │   │                       ├── icon_300.png
    │   │                       ├── icon_400.png
    │   │                       ├── icon_600.png
    │   │                       └── icon_800.png
    │   ├── devices.json
    │   └── README.md
    ├── .replit-artifact/
    │   └── artifact.toml
    ├── android/
    │   ├── .gradle/
    │   │   ├── 8.14.3/
    │   │   │   ├── checksums/
    │   │   │   │   ├── checksums.lock
    │   │   │   │   ├── md5-checksums.bin
    │   │   │   │   └── sha1-checksums.bin
    │   │   │   └── fileHashes/
    │   │   │       └── fileHashes.lock
    │   │   └── buildOutputCleanup/
    │   │       ├── buildOutputCleanup.lock
    │   │       └── cache.properties
    │   ├── app/
    │   │   ├── src/
    │   │   │   ├── debug/
    │   │   │   │   └── AndroidManifest.xml
    │   │   │   ├── debugOptimized/
    │   │   │   │   └── AndroidManifest.xml
    │   │   │   └── main/
    │   │   │       ├── java/
    │   │   │       │   └── com/
    │   │   │       │       └── anonymous/
    │   │   │       │           └── skmobile/
    │   │   │       │               ├── MainActivity.kt
    │   │   │       │               └── MainApplication.kt
    │   │   │       ├── res/
    │   │   │       │   ├── drawable/
    │   │   │       │   │   ├── ic_launcher_background.xml
    │   │   │       │   │   └── rn_edit_text_material.xml
    │   │   │       │   ├── drawable-hdpi/
    │   │   │       │   │   └── splashscreen_logo.png
    │   │   │       │   ├── drawable-mdpi/
    │   │   │       │   │   └── splashscreen_logo.png
    │   │   │       │   ├── drawable-xhdpi/
    │   │   │       │   │   └── splashscreen_logo.png
    │   │   │       │   ├── drawable-xxhdpi/
    │   │   │       │   │   └── splashscreen_logo.png
    │   │   │       │   ├── drawable-xxxhdpi/
    │   │   │       │   │   └── splashscreen_logo.png
    │   │   │       │   ├── mipmap-hdpi/
    │   │   │       │   │   ├── ic_launcher_foreground.webp
    │   │   │       │   │   └── ic_launcher.webp
    │   │   │       │   ├── mipmap-mdpi/
    │   │   │       │   │   ├── ic_launcher_foreground.webp
    │   │   │       │   │   └── ic_launcher.webp
    │   │   │       │   ├── mipmap-xhdpi/
    │   │   │       │   │   ├── ic_launcher_foreground.webp
    │   │   │       │   │   └── ic_launcher.webp
    │   │   │       │   ├── mipmap-xxhdpi/
    │   │   │       │   │   ├── ic_launcher_foreground.webp
    │   │   │       │   │   └── ic_launcher.webp
    │   │   │       │   ├── mipmap-xxxhdpi/
    │   │   │       │   │   ├── ic_launcher_foreground.webp
    │   │   │       │   │   └── ic_launcher.webp
    │   │   │       │   ├── values/
    │   │   │       │   │   ├── colors.xml
    │   │   │       │   │   ├── strings.xml
    │   │   │       │   │   └── styles.xml
    │   │   │       │   └── values-night/
    │   │   │       │       └── colors.xml
    │   │   │       └── AndroidManifest.xml
    │   │   ├── build.gradle
    │   │   ├── debug.keystore
    │   │   └── proguard-rules.pro
    │   ├── gradle/
    │   │   └── wrapper/
    │   │       ├── gradle-wrapper.jar
    │   │       └── gradle-wrapper.properties
    │   ├── .gitignore
    │   ├── build.gradle
    │   ├── gradle.properties
    │   ├── gradlew
    │   ├── gradlew.bat
    │   └── settings.gradle
    ├── app/
    │   ├── (tabs)/
    │   │   ├── _layout.tsx
    │   │   ├── clientes.tsx
    │   │   ├── configuracoes.tsx
    │   │   ├── iara.tsx
    │   │   ├── index.tsx
    │   │   ├── juridico.tsx
    │   │   └── processos.tsx
    │   ├── _layout.tsx
    │   └── +not-found.tsx
    ├── assets/
    │   └── images/
    │       └── icon.png
    ├── components/
    │   ├── ErrorBoundary.tsx
    │   ├── ErrorFallback.tsx
    │   └── KeyboardAwareScrollViewCompat.tsx
    ├── constants/
    │   └── colors.ts
    ├── hooks/
    │   └── useColors.ts
    ├── scripts/
    │   └── build.js
    ├── server/
    │   ├── templates/
    │   │   └── landing-page.html
    │   └── serve.js
    ├── .gitignore
    ├── app.json
    ├── babel.config.js
    ├── eas.json
    ├── expo-env.d.ts
    ├── metro.config.js
    ├── package.json
    └── tsconfig.json
```

---

## STACK TECNOLOGICO DETECTADO

- **Frontend:** React, TypeScript

---

## ROTAS DA API (endpoints detectados automaticamente)

```
GET    /api/items  (em sk-editor/dist/public/assets/index-Dn05cZXz.js)
GET    /api/items/:id  (em sk-editor/dist/public/assets/index-Dn05cZXz.js)
POST   /api/items  (em sk-editor/dist/public/assets/index-Dn05cZXz.js)
GET    /api/health  (em sk-editor/dist/public/assets/index-Dn05cZXz.js)
USE    /api/auth  (em sk-editor/dist/public/assets/index-Dn05cZXz.js)
USE    /api/usuarios  (em sk-editor/dist/public/assets/index-Dn05cZXz.js)
POST   /register  (em sk-editor/dist/public/assets/index-Dn05cZXz.js)
POST   /login  (em sk-editor/dist/public/assets/index-Dn05cZXz.js)
GET    /perfil  (em sk-editor/dist/public/assets/index-Dn05cZXz.js)
GET    /api/provedores  (em sk-editor/dist/public/assets/index-Dn05cZXz.js)
POST   /api/chat  (em sk-editor/dist/public/assets/index-Dn05cZXz.js)
GET    /health  (em sk-editor/dist/public/assets/index-Dn05cZXz.js)
POST   /auth/login  (em sk-editor/dist/public/assets/index-Dn05cZXz.js)
POST   /auth/registro  (em sk-editor/dist/public/assets/index-Dn05cZXz.js)
GET    /clientes  (em sk-editor/dist/public/assets/index-Dn05cZXz.js)
GET    /clientes/:id  (em sk-editor/dist/public/assets/index-Dn05cZXz.js)
POST   /clientes  (em sk-editor/dist/public/assets/index-Dn05cZXz.js)
PUT    /clientes/:id  (em sk-editor/dist/public/assets/index-Dn05cZXz.js)
GET    /processos  (em sk-editor/dist/public/assets/index-Dn05cZXz.js)
GET    /processos/:id  (em sk-editor/dist/public/assets/index-Dn05cZXz.js)
POST   /processos  (em sk-editor/dist/public/assets/index-Dn05cZXz.js)
GET    /audiencias  (em sk-editor/dist/public/assets/index-Dn05cZXz.js)
POST   /audiencias  (em sk-editor/dist/public/assets/index-Dn05cZXz.js)
GET    /prazos/proximos  (em sk-editor/dist/public/assets/index-Dn05cZXz.js)
GET    /dashboard  (em sk-editor/dist/public/assets/index-Dn05cZXz.js)
GET    /api/registros  (em sk-editor/dist/public/assets/index-Dn05cZXz.js)
GET    /api/registros/:id  (em sk-editor/dist/public/assets/index-Dn05cZXz.js)
POST   /api/registros  (em sk-editor/dist/public/assets/index-Dn05cZXz.js)
PUT    /api/registros/:id  (em sk-editor/dist/public/assets/index-Dn05cZXz.js)
DELETE /api/registros/:id  (em sk-editor/dist/public/assets/index-Dn05cZXz.js)
GET    /api/items  (em sk-editor/src/lib/templates.ts)
GET    /api/items/:id  (em sk-editor/src/lib/templates.ts)
POST   /api/items  (em sk-editor/src/lib/templates.ts)
GET    /api/health  (em sk-editor/src/lib/templates.ts)
USE    /api/auth  (em sk-editor/src/lib/templates.ts)
USE    /api/usuarios  (em sk-editor/src/lib/templates.ts)
POST   /register  (em sk-editor/src/lib/templates.ts)
POST   /login  (em sk-editor/src/lib/templates.ts)
GET    /perfil  (em sk-editor/src/lib/templates.ts)
GET    /api/provedores  (em sk-editor/src/lib/templates.ts)
POST   /api/chat  (em sk-editor/src/lib/templates.ts)
GET    /health  (em sk-editor/src/lib/templates.ts)
POST   /auth/login  (em sk-editor/src/lib/templates.ts)
POST   /auth/registro  (em sk-editor/src/lib/templates.ts)
GET    /clientes  (em sk-editor/src/lib/templates.ts)
GET    /clientes/:id  (em sk-editor/src/lib/templates.ts)
POST   /clientes  (em sk-editor/src/lib/templates.ts)
PUT    /clientes/:id  (em sk-editor/src/lib/templates.ts)
GET    /processos  (em sk-editor/src/lib/templates.ts)
GET    /processos/:id  (em sk-editor/src/lib/templates.ts)
POST   /processos  (em sk-editor/src/lib/templates.ts)
GET    /audiencias  (em sk-editor/src/lib/templates.ts)
POST   /audiencias  (em sk-editor/src/lib/templates.ts)
GET    /prazos/proximos  (em sk-editor/src/lib/templates.ts)
GET    /dashboard  (em sk-editor/src/lib/templates.ts)
GET    /api/registros  (em sk-editor/src/lib/templates.ts)
GET    /api/registros/:id  (em sk-editor/src/lib/templates.ts)
POST   /api/registros  (em sk-editor/src/lib/templates.ts)
PUT    /api/registros/:id  (em sk-editor/src/lib/templates.ts)
DELETE /api/registros/:id  (em sk-editor/src/lib/templates.ts)
```

---

## VARIAVEIS DE AMBIENTE NECESSARIAS

Crie um arquivo `.env` na raiz com estas variaveis:

```env
APP_URL=seu_valor_aqui
PORT=seu_valor_aqui
BASE_PATH=seu_valor_aqui
REPL_ID=seu_valor_aqui
ALLOWED_ORIGINS=seu_valor_aqui
JWT_SECRET=seu_valor_aqui
JWT_EXPIRES_IN=seu_valor_aqui
DATABASE_URL=seu_valor_aqui
GROQ_API_KEY=seu_valor_aqui
OPENAI_API_KEY=seu_valor_aqui
GEMINI_API_KEY=seu_valor_aqui
ANTHROPIC_API_KEY=seu_valor_aqui
XAI_API_KEY=seu_valor_aqui
OPENROUTER_API_KEY=seu_valor_aqui
PERPLEXITY_API_KEY=seu_valor_aqui
TELEGRAM_TOKEN=seu_valor_aqui
REPLIT_INTERNAL_APP_DOMAIN=seu_valor_aqui
REPLIT_DEV_DOMAIN=seu_valor_aqui
EXPO_PUBLIC_DOMAIN=seu_valor_aqui
EXPO_PUBLIC_REPL_ID=seu_valor_aqui
```

---

## ARQUIVOS PRINCIPAIS

- `apk-builder/dist/public/index.html` — Arquivo principal
- `apk-builder/index.html` — Arquivo principal
- `apk-builder/src/App.tsx` — Componente raiz do frontend
- `apk-builder/src/main.tsx` — Arquivo principal
- `assistente-juridico/android/app/src/main/assets/public/index.html` — Arquivo principal
- `assistente-juridico/dist/index.html` — Arquivo principal
- `assistente-juridico/dist/public/index.html` — Arquivo principal
- `juridico/dist/public/index.html` — Arquivo principal
- `juridico/index.html` — Arquivo principal
- `juridico/src/App.tsx` — Componente raiz do frontend

---

## GUIA COMPLETO — O QUE CADA PARTE DO PROJETO FAZ

> Esta secao explica, em linguagem simples, o que e para que serve cada pasta e cada arquivo.

### 📁 `apk-builder/`
> Pasta 'apk-builder' — agrupamento de arquivos relacionados.

**`components.json`** _(20 linhas)_
Arquivo de dados ou configuracao no formato JSON (chave: valor).

**`index.html`** _(40 linhas)_
Pagina HTML raiz do projeto. E o ponto de entrada que o browser carrega primeiro.

**`package.json`** _(91 linhas)_
Registro de dependencias e scripts do projeto. Aqui ficam os comandos (npm run dev, npm start) e os pacotes instalados.

**`tsconfig.json`** _(19 linhas)_
Configuracao do TypeScript. Diz para o computador como interpretar o codigo .ts e .tsx.

**`vite.config.ts`** _(53 linhas)_
Configuracao do Vite (servidor de desenvolvimento). Define a porta, alias de caminhos e plugins usados.

---

### 📁 `juridico/`
> Pasta 'juridico' — agrupamento de arquivos relacionados.

**`components.json`** _(20 linhas)_
Arquivo de dados ou configuracao no formato JSON (chave: valor).

**`index.html`** _(41 linhas)_
Pagina HTML raiz do projeto. E o ponto de entrada que o browser carrega primeiro.

**`package.json`** _(102 linhas)_
Registro de dependencias e scripts do projeto. Aqui ficam os comandos (npm run dev, npm start) e os pacotes instalados.

**`tsconfig.json`** _(23 linhas)_
Configuracao do TypeScript. Diz para o computador como interpretar o codigo .ts e .tsx.

**`vite.config.ts`** _(123 linhas)_
Configuracao do Vite (servidor de desenvolvimento). Define a porta, alias de caminhos e plugins usados.

---

### 📁 `sk-editor/`
> Pasta 'sk-editor' — agrupamento de arquivos relacionados.

**`SYSTEM_DOCS.md`** _(292 linhas)_
Arquivo de documentacao em Markdown (texto formatado com #titulos, **negrito**, listas).

**`components.json`** _(20 linhas)_
Arquivo de dados ou configuracao no formato JSON (chave: valor).

**`index.html`** _(98 linhas)_
Pagina HTML raiz do projeto. E o ponto de entrada que o browser carrega primeiro.

**`package.json`** _(93 linhas)_
Registro de dependencias e scripts do projeto. Aqui ficam os comandos (npm run dev, npm start) e os pacotes instalados.

**`tsconfig.json`** _(23 linhas)_
Configuracao do TypeScript. Diz para o computador como interpretar o codigo .ts e .tsx.

**`vite.config.ts`** _(69 linhas)_
Configuracao do Vite (servidor de desenvolvimento). Define a porta, alias de caminhos e plugins usados.

---

### 📁 `sk-mobile/`
> Pasta 'sk-mobile' — agrupamento de arquivos relacionados.

**`.gitignore`** _(42 linhas)_
Lista de arquivos/pastas que o Git deve IGNORAR (nao versionar). Ex: node_modules, .env

**`app.json`** _(41 linhas)_
Arquivo de dados ou configuracao no formato JSON (chave: valor).

**`babel.config.js`** _(7 linhas)_
Arquivo de CONSTANTES/CONFIGURACAO — valores fixos usados em varios lugares do projeto.

**`eas.json`** _(33 linhas)_
Arquivo de dados ou configuracao no formato JSON (chave: valor).

**`expo-env.d.ts`** _(3 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`metro.config.js`** _(4 linhas)_
Arquivo de CONSTANTES/CONFIGURACAO — valores fixos usados em varios lugares do projeto.

**`package.json`** _(67 linhas)_
Registro de dependencias e scripts do projeto. Aqui ficam os comandos (npm run dev, npm start) e os pacotes instalados.

**`tsconfig.json`** _(24 linhas)_
Configuracao do TypeScript. Diz para o computador como interpretar o codigo .ts e .tsx.

---

### 📁 `apk-builder/.replit-artifact/`
> Pasta '.replit-artifact' — agrupamento de arquivos relacionados.

**`artifact.toml`** _(32 linhas)_
Arquivo TOML — parte do projeto.

---

### 📁 `apk-builder/public/`
> Arquivos estaticos: imagens, icones, fontes, arquivos publicos.

**`favicon.svg`** _(4 linhas)_
Imagem vetorial (icone ou ilustracao que nao perde qualidade ao ampliar).

**`icon-192.png`** _(1 linha)_
Arquivo de imagem.

**`icon-192.svg`** _(12 linhas)_
Imagem vetorial (icone ou ilustracao que nao perde qualidade ao ampliar).

**`icon-512.png`** _(1 linha)_
Arquivo de imagem.

**`icon-512.svg`** _(17 linhas)_
Imagem vetorial (icone ou ilustracao que nao perde qualidade ao ampliar).

**`manifest.json`** _(45 linhas)_
Manifesto do PWA — define nome, icone e configuracoes para instalar o app no celular.

**`opengraph.jpg`** _(1 linha)_
Arquivo de imagem.

**`sw.js`** _(71 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

---

### 📁 `apk-builder/src/`
> Codigo-fonte principal do projeto. Nao apague esta pasta.

**`App.tsx`** _(2251 linhas)_
Componente RAIZ do frontend — e o pai de todos os outros componentes. Aqui ficam as rotas principais.

**`index.css`** _(62 linhas)_
Arquivo de estilos visuais — cores, tamanhos, fontes, espacamentos da interface.

**`main.tsx`** _(6 linhas)_
Ponto de entrada do React — monta o componente App na pagina HTML.

---

### 📁 `assistente-juridico/android/`
> Pasta 'android' — agrupamento de arquivos relacionados.

**`local.properties`** _(2 linhas)_
Arquivo PROPERTIES — parte do projeto.

---

### 📁 `assistente-juridico/dist/`
> Codigo compilado/gerado automaticamente — NAO edite diretamente.

**`cordova.js`** _(1 linha)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`cordova_plugins.js`** _(1 linha)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`favicon.svg`** _(4 linhas)_
Imagem vetorial (icone ou ilustracao que nao perde qualidade ao ampliar).

**`icon-192.png`** _(1 linha)_
Arquivo de imagem.

**`icon-384.png`** _(1 linha)_
Arquivo de imagem.

**`icon-512.png`** _(1 linha)_
Arquivo de imagem.

**`icon-96.png`** _(1 linha)_
Arquivo de imagem.

**`index.html`** _(54 linhas)_
Pagina HTML raiz do projeto. E o ponto de entrada que o browser carrega primeiro.

**`manifest.json`** _(64 linhas)_
Manifesto do PWA — define nome, icone e configuracoes para instalar o app no celular.

**`opengraph.jpg`** _(1 linha)_
Arquivo de imagem.

**`robots.txt`** _(3 linhas)_
Arquivo TXT — parte do projeto.

**`sw.js`** _(202 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

---

### 📁 `juridico/.replit-artifact/`
> Pasta '.replit-artifact' — agrupamento de arquivos relacionados.

**`artifact.toml`** _(32 linhas)_
Arquivo TOML — parte do projeto.

---

### 📁 `juridico/public/`
> Arquivos estaticos: imagens, icones, fontes, arquivos publicos.

**`favicon.svg`** _(10 linhas)_
Imagem vetorial (icone ou ilustracao que nao perde qualidade ao ampliar).

**`opengraph.jpg`** _(1 linha)_
Arquivo de imagem.

**`robots.txt`** _(3 linhas)_
Arquivo TXT — parte do projeto.

---

### 📁 `juridico/src/`
> Codigo-fonte principal do projeto. Nao apague esta pasta.

**`App.tsx`** _(172 linhas)_
Componente RAIZ do frontend — e o pai de todos os outros componentes. Aqui ficam as rotas principais.

**`index.css`** _(519 linhas)_
Arquivo de estilos visuais — cores, tamanhos, fontes, espacamentos da interface.

**`main.tsx`** _(9 linhas)_
Ponto de entrada do React — monta o componente App na pagina HTML.

---

### 📁 `sk-editor/.replit-artifact/`
> Pasta '.replit-artifact' — agrupamento de arquivos relacionados.

**`artifact.toml`** _(32 linhas)_
Arquivo TOML — parte do projeto.

---

### 📁 `sk-editor/public/`
> Arquivos estaticos: imagens, icones, fontes, arquivos publicos.

**`MANUAL-SK-CODE-EDITOR.md`** _(344 linhas)_
Arquivo de documentacao em Markdown (texto formatado com #titulos, **negrito**, listas).

**`favicon.svg`** _(17 linhas)_
Imagem vetorial (icone ou ilustracao que nao perde qualidade ao ampliar).

**`guia-completo-apk.md`** _(949 linhas)_
Arquivo de documentacao em Markdown (texto formatado com #titulos, **negrito**, listas).

**`icon-192.png`** _(1 linha)_
Arquivo de imagem.

**`icon-512.png`** _(1 linha)_
Arquivo de imagem.

**`manifest.json`** _(52 linhas)_
Manifesto do PWA — define nome, icone e configuracoes para instalar o app no celular.

**`manual-dev.md`** _(281 linhas)_
Arquivo de documentacao em Markdown (texto formatado com #titulos, **negrito**, listas).

**`opengraph.jpg`** _(1 linha)_
Arquivo de imagem.

**`sw.js`** _(186 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

---

### 📁 `sk-editor/src/`
> Codigo-fonte principal do projeto. Nao apague esta pasta.

**`App.tsx`** _(218 linhas)_
Componente RAIZ do frontend — e o pai de todos os outros componentes. Aqui ficam as rotas principais.

**`index.css`** _(167 linhas)_
Arquivo de estilos visuais — cores, tamanhos, fontes, espacamentos da interface.

**`main.tsx`** _(6 linhas)_
Ponto de entrada do React — monta o componente App na pagina HTML.

---

### 📁 `sk-mobile/.expo/`
> Pasta '.expo' — agrupamento de arquivos relacionados.

**`README.md`** _(14 linhas)_
Documentacao principal do projeto. Explica o que o projeto faz e como rodar.

**`devices.json`** _(4 linhas)_
Arquivo de dados ou configuracao no formato JSON (chave: valor).

---

### 📁 `sk-mobile/.replit-artifact/`
> Pasta '.replit-artifact' — agrupamento de arquivos relacionados.

**`artifact.toml`** _(28 linhas)_
Arquivo TOML — parte do projeto.

---

### 📁 `sk-mobile/android/`
> Pasta 'android' — agrupamento de arquivos relacionados.

**`.gitignore`** _(17 linhas)_
Lista de arquivos/pastas que o Git deve IGNORAR (nao versionar). Ex: node_modules, .env

**`build.gradle`** _(25 linhas)_
Arquivo GRADLE — parte do projeto.

**`gradle.properties`** _(66 linhas)_
Arquivo PROPERTIES — parte do projeto.

**`gradlew`** _(252 linhas)_
Arquivo GRADLEW — parte do projeto.

**`gradlew.bat`** _(95 linhas)_
Arquivo BAT — parte do projeto.

**`settings.gradle`** _(40 linhas)_
Arquivo GRADLE — parte do projeto.

---

### 📁 `sk-mobile/app/`
> Pasta 'app' — agrupamento de arquivos relacionados.

**`+not-found.tsx`** _(46 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`_layout.tsx`** _(76 linhas)_
Componente de LAYOUT — define a estrutura visual da pagina (cabecalho, sidebar, rodape). Envolve outros componentes.

---

### 📁 `sk-mobile/components/`
> Pecas visuais reutilizaveis da interface (botoes, cards, formularios...).

**`ErrorBoundary.tsx`** _(55 linhas)_
Componente de ERRO — exibido quando algo da errado, com mensagem explicativa.

**`ErrorFallback.tsx`** _(279 linhas)_
Componente de ERRO — exibido quando algo da errado, com mensagem explicativa.

**`KeyboardAwareScrollViewCompat.tsx`** _(30 linhas)_
Componente de PAGINA/TELA — representa uma tela completa navegavel no app.

---

### 📁 `sk-mobile/constants/`
> Pasta 'constants' — agrupamento de arquivos relacionados.

**`colors.ts`** _(46 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

---

### 📁 `sk-mobile/hooks/`
> Hooks React customizados — logica reutilizavel de estado e efeitos.

**`useColors.ts`** _(25 linhas)_
HOOK React personalizado para gerenciar estado/comportamento de 'colors'.

---

### 📁 `sk-mobile/scripts/`
> Pasta 'scripts' — agrupamento de arquivos relacionados.

**`build.js`** _(574 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

---

### 📁 `sk-mobile/server/`
> Pasta 'server' — agrupamento de arquivos relacionados.

**`serve.js`** _(136 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

---

### 📁 `apk-builder/dist/public/`
> Arquivos estaticos: imagens, icones, fontes, arquivos publicos.

**`assistente-juridico-pwa.zip`** _(1 linha)_
Arquivo ZIP — parte do projeto.

**`favicon.svg`** _(4 linhas)_
Imagem vetorial (icone ou ilustracao que nao perde qualidade ao ampliar).

**`icon-192.png`** _(1 linha)_
Arquivo de imagem.

**`icon-192.svg`** _(12 linhas)_
Imagem vetorial (icone ou ilustracao que nao perde qualidade ao ampliar).

**`icon-512.png`** _(1 linha)_
Arquivo de imagem.

**`icon-512.svg`** _(17 linhas)_
Imagem vetorial (icone ou ilustracao que nao perde qualidade ao ampliar).

**`index.html`** _(41 linhas)_
Pagina HTML raiz do projeto. E o ponto de entrada que o browser carrega primeiro.

**`manifest.json`** _(45 linhas)_
Manifesto do PWA — define nome, icone e configuracoes para instalar o app no celular.

**`opengraph.jpg`** _(1 linha)_
Arquivo de imagem.

**`sw.js`** _(71 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

---

### 📁 `apk-builder/src/components/`
> Pecas visuais reutilizaveis da interface (botoes, cards, formularios...).

**`ApkAnalyzer.tsx`** _(399 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`TerminalTab.tsx`** _(826 linhas)_
Componente de ABAS — permite alternar entre diferentes secoes de conteudo com clique.

**`XTermConnector.tsx`** _(276 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

---

### 📁 `apk-builder/src/hooks/`
> Hooks React customizados — logica reutilizavel de estado e efeitos.

**`use-mobile.tsx`** _(20 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`use-toast.ts`** _(192 linhas)_
HOOK React personalizado para gerenciar estado/comportamento de '-toast'.

---

### 📁 `apk-builder/src/lib/`
> Funcoes auxiliares reutilizaveis em varios lugares do projeto.

**`android.ts`** _(863 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`archive.ts`** _(319 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`github.ts`** _(342 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`storage.ts`** _(123 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`utils.ts`** _(7 linhas)_
Funcoes UTILITARIAS — ferramentas reutilizaveis de uso geral no projeto.

---

### 📁 `apk-builder/src/pages/`
> Telas completas do app — cada arquivo aqui e uma pagina navegavel.

**`not-found.tsx`** _(22 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

---

### 📁 `assistente-juridico/android/capacitor-cordova-android-plugins/`
> Pasta 'capacitor-cordova-android-plugins' — agrupamento de arquivos relacionados.

**`build.gradle`** _(59 linhas)_
Arquivo GRADLE — parte do projeto.

**`cordova.variables.gradle`** _(7 linhas)_
Arquivo GRADLE — parte do projeto.

---

### 📁 `assistente-juridico/dist/assets/`
> Arquivos estaticos: imagens, icones, fontes, arquivos publicos.

**`admin-DdVWhbJZ.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`arrow-left-nBCyQW32.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`assinatura-DhMNHOKB.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`badge-CeQ9YgHg.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`bell-S8SoMvhJ.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`book-open-jGqVCAaa.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`bot-BPZdrzKs.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`briefcase-JIjjIAIQ.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`building-2-DuXwQ01A.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`button-DogYNL8m.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`calendar-C8eS9BJ3.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`card-CAMPMs4I.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`check-Cw4MhVxd.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`chevron-down-CSLxLrLQ.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`chevron-left-D8dWNoIe.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`chevron-right-QUxraXO5.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`chevron-up-B-NrD1Yf.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`circle-CpSIygtO.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`circle-alert-CODgC0Wt.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`circle-check-BvyNknoB.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`circle-x-BI8lMh8t.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`clock-Cp3l2mis.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`codigo-CBvzBZYN.js`** _(9 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`colaborativo-Bmjhl7Bs.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`comparador-juridico-e11bTEP1.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`comunicacoes-cnj-DF3LmGtR.js`** _(9 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`configuracoes-DyhSBsZW.js`** _(26 linhas)_
Arquivo de CONSTANTES/CONFIGURACAO — valores fixos usados em varios lugares do projeto.

**`consulta-corporativo-AH19UW8F.js`** _(5 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`consulta-pdpj-CmwGfWNe.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`consulta-processual-DT9PR3AD.js`** _(13 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`copy-BJbuHhiB.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`cpu-H9bqy-ol.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`database-DPXDRvNh.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`dialog-BW4Lb6A6.js`** _(6 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`download-CYbqGIYu.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`ementas-GuvS-wAN.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`escritorio-D5Xc-ipL.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`external-link-CEf6uMDg.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`eye-NEq-3FD4.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`eye-off-BkyV4iqA.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`file-text-CVJYXn7I.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`filtrador-Uh5o5CGF.js`** _(40 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`gavel-7xOSQuEL.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`globe-DqXCJqaQ.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`hash-DXrFETIG.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`historico-BHc_45HR.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`history-Dm5s-98n.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`index-B-_-zVh9.js`** _(222 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`index-BdQq_4o_.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`index-Cajry1w2.js`** _(42 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`index-DGVWKFBB.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`index-Dha_x3eW.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`index-Do0OOi2v.css`** _(2 linhas)_
Arquivo de estilos visuais — cores, tamanhos, fontes, espacamentos da interface.

**`index-Dt5FInq3.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`index-ZJT4jjP1.js`** _(11 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`info-Bv65dD_K.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`input-BsVrziBy.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`jurisprudencia-OuGxXOY4.js`** _(75 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`key-Ba8qnwem.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`label-Cc5cm9uG.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`legal-assistant-v7qssgXW.js`** _(113 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`log-out-C1v4nIPP.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`login-7hMOiJ2J.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`mail-DIZQZj_s.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`message-square-D_Z2gJKw.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`not-found-DSZWET4-.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`painel-processos-B7i2NMof.js`** _(13 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`pdf-B75MOh95.js`** _(56 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`pencil-Q_CBYcqn.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`pje-9CSE9fDi.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`play-DfmtkRyB.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`playground-DD29hz3O.js`** _(390 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`plus-DfNIQMpt.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`prazos-DF6K-tvm.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`previdenciario-DkaB0ujZ.js`** _(10 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`refresh-cw-D5__vk8G.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`robo-djen-D3WPdr0u.js`** _(5 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`rotate-ccw-D28OuoVq.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`save-BnF37M3_.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`scale-i6eM2OQ9.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`search-B1p4_U_k.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`select-DutfNDZp.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`separator-DQXp5lNG.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`server-DNeVClqP.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`settings-Cudh-Mnh.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`shield-CeeBT9p1.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`slider-D0R0PB6j.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`status-B5oxDYuU.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`tabs-DnoBjg6K.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`tag-B3no2Wh0.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`target-BCM4Kr-t.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`templates-juridicos-1Iq21zIV.js`** _(646 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`terminal-BajxkcBh.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`textarea-CDo_t3Pz.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`theme-toggle-DD5PSROF.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`tiptap-editor-DxlsD-7E.js`** _(154 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`token-generator-OcTrrzh7.js`** _(27 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`tramitacao-BxlsSwUG.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`trash-2-DDvNxfXN.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`triangle-alert-DSonC7Kt.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`upload-Bl3wdvk6.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`useMutation-DjoeqaNn.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`user-7yy-BCdS.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`user-check-vp_bBrF6.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`users-DONy9nTq.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`volume-x-DcwW5KKL.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`wifi-B6Kj2hWi.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`zap-uo4Z6IN6.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

---

### 📁 `assistente-juridico/dist/public/`
> Arquivos estaticos: imagens, icones, fontes, arquivos publicos.

**`SK-Juridico-IA-v1.8.apk`** _(1 linha)_
Arquivo APK — parte do projeto.

**`SK-Juridico-IA.apk`** _(1 linha)_
Arquivo APK — parte do projeto.

**`favicon.svg`** _(4 linhas)_
Imagem vetorial (icone ou ilustracao que nao perde qualidade ao ampliar).

**`icon-192.png`** _(1 linha)_
Arquivo de imagem.

**`icon-384.png`** _(1 linha)_
Arquivo de imagem.

**`icon-512.png`** _(1 linha)_
Arquivo de imagem.

**`icon-96.png`** _(1 linha)_
Arquivo de imagem.

**`index.html`** _(54 linhas)_
Pagina HTML raiz do projeto. E o ponto de entrada que o browser carrega primeiro.

**`manifest.json`** _(64 linhas)_
Manifesto do PWA — define nome, icone e configuracoes para instalar o app no celular.

**`opengraph.jpg`** _(1 linha)_
Arquivo de imagem.

**`robots.txt`** _(3 linhas)_
Arquivo TXT — parte do projeto.

**`setup-preview.html`** _(72 linhas)_
Arquivo HTML — parte do projeto.

**`sw.js`** _(202 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

---

### 📁 `juridico/dist/public/`
> Arquivos estaticos: imagens, icones, fontes, arquivos publicos.

**`favicon.svg`** _(10 linhas)_
Imagem vetorial (icone ou ilustracao que nao perde qualidade ao ampliar).

**`index.html`** _(42 linhas)_
Pagina HTML raiz do projeto. E o ponto de entrada que o browser carrega primeiro.

**`manifest.webmanifest`** _(2 linhas)_
Arquivo WEBMANIFEST — parte do projeto.

**`opengraph.jpg`** _(1 linha)_
Arquivo de imagem.

**`registerSW.js`** _(1 linha)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`robots.txt`** _(3 linhas)_
Arquivo TXT — parte do projeto.

**`sw.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`workbox-6829fd8d.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

---

### 📁 `juridico/public/icons/`
> Icones do projeto.

**`icon-128x128.svg`** _(8 linhas)_
Imagem vetorial (icone ou ilustracao que nao perde qualidade ao ampliar).

**`icon-144x144.svg`** _(8 linhas)_
Imagem vetorial (icone ou ilustracao que nao perde qualidade ao ampliar).

**`icon-152x152.svg`** _(8 linhas)_
Imagem vetorial (icone ou ilustracao que nao perde qualidade ao ampliar).

**`icon-192x192.svg`** _(8 linhas)_
Imagem vetorial (icone ou ilustracao que nao perde qualidade ao ampliar).

**`icon-384x384.svg`** _(8 linhas)_
Imagem vetorial (icone ou ilustracao que nao perde qualidade ao ampliar).

**`icon-512x512.svg`** _(8 linhas)_
Imagem vetorial (icone ou ilustracao que nao perde qualidade ao ampliar).

**`icon-72x72.svg`** _(8 linhas)_
Imagem vetorial (icone ou ilustracao que nao perde qualidade ao ampliar).

**`icon-96x96.svg`** _(8 linhas)_
Imagem vetorial (icone ou ilustracao que nao perde qualidade ao ampliar).

---

### 📁 `juridico/src/components/`
> Pecas visuais reutilizaveis da interface (botoes, cards, formularios...).

**`Layout.tsx`** _(70 linhas)_
Componente de LAYOUT — define a estrutura visual da pagina (cabecalho, sidebar, rodape). Envolve outros componentes.

**`PinLock.tsx`** _(114 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`pwa-install.tsx`** _(72 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`theme-provider.tsx`** _(47 linhas)_
Componente PROVIDER — 'fornece' dados/funcoes para todos os componentes filhos via Context API do React.

**`theme-toggle.tsx`** _(19 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`tiptap-editor.tsx`** _(416 linhas)_
Componente EDITOR — area de edicao de texto, codigo ou conteudo rico.

---

### 📁 `juridico/src/hooks/`
> Hooks React customizados — logica reutilizavel de estado e efeitos.

**`use-mobile.tsx`** _(20 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`use-toast.ts`** _(192 linhas)_
HOOK React personalizado para gerenciar estado/comportamento de '-toast'.

**`useLocalStorage.ts`** _(15 linhas)_
HOOK de armazenamento local — salva e recupera dados do localStorage do browser.

---

### 📁 `juridico/src/lib/`
> Funcoes auxiliares reutilizaveis em varios lugares do projeto.

**`aiDirect.ts`** _(187 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`apiInterceptor.ts`** _(587 linhas)_
Arquivo de SERVICO/API — funcoes para comunicar com o servidor ou API externa.

**`fileExtract.ts`** _(77 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`legal-formatter.ts`** _(131 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`localDB.ts`** _(142 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`queryClient.ts`** _(58 linhas)_
Arquivo de SERVICO/API — funcoes para comunicar com o servidor ou API externa.

**`speech.ts`** _(122 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`storage.ts`** _(33 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`sync-storage.ts`** _(271 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`tts-service.ts`** _(312 linhas)_
Arquivo de SERVICO/API — funcoes para comunicar com o servidor ou API externa.

**`utils.ts`** _(7 linhas)_
Funcoes UTILITARIAS — ferramentas reutilizaveis de uso geral no projeto.

---

### 📁 `juridico/src/pages/`
> Telas completas do app — cada arquivo aqui e uma pagina navegavel.

**`Assistente.tsx`** _(946 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`Audiencias.tsx`** _(125 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`Clientes.tsx`** _(103 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`ComunicacoesProcessuais.tsx`** _(156 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`Configuracoes.tsx`** _(651 linhas)_
Componente de CONFIGURACOES — tela onde o usuario ajusta preferencias do app.

**`Dashboard.tsx`** _(84 linhas)_
Componente de PAINEL DE CONTROLE — tela principal com resumo de dados e acesso rapido as funcoes.

**`Documentos.tsx`** _(90 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`ExtractorJuridico.tsx`** _(691 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`HtmlPlayground.tsx`** _(185 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`Processos.tsx`** _(139 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`Templates.tsx`** _(249 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`admin.tsx`** _(384 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`assinatura.tsx`** _(361 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`auditoria-financeira.tsx`** _(25 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`codigo.tsx`** _(1000 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`colaborativo.tsx`** _(450 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`comparador-juridico.tsx`** _(25 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`comunicacoes-cnj.tsx`** _(403 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`configuracoes.tsx`** _(1584 linhas)_
Componente de CONFIGURACOES — tela onde o usuario ajusta preferencias do app.

**`consulta-corporativo.tsx`** _(479 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`consulta-pdpj.tsx`** _(671 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`consulta-processual.tsx`** _(656 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`ementas.tsx`** _(152 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`escritorio.tsx`** _(359 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`filtrador.tsx`** _(732 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`guia.tsx`** _(382 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`historico.tsx`** _(137 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`iara.tsx`** _(905 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`juridico-pro.tsx`** _(965 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`jurisprudencia.tsx`** _(3837 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`legal-assistant.tsx`** _(5402 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`login.tsx`** _(105 linhas)_
Componente de LOGIN/AUTENTICACAO — tela de entrada com usuario e senha.

**`not-found.tsx`** _(33 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`painel-processos.tsx`** _(758 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`pje.tsx`** _(292 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`playground.tsx`** _(1475 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`prazos.tsx`** _(392 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`previdenciario.tsx`** _(770 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`robo-djen.tsx`** _(1053 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`status.tsx`** _(259 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`templates-juridicos.tsx`** _(1108 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`token-generator.tsx`** _(450 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`tramitacao.tsx`** _(828 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

---

### 📁 `sk-editor/dist/public/`
> Arquivos estaticos: imagens, icones, fontes, arquivos publicos.

**`MANUAL-SK-CODE-EDITOR.md`** _(344 linhas)_
Arquivo de documentacao em Markdown (texto formatado com #titulos, **negrito**, listas).

**`favicon.svg`** _(17 linhas)_
Imagem vetorial (icone ou ilustracao que nao perde qualidade ao ampliar).

**`guia-completo-apk.md`** _(949 linhas)_
Arquivo de documentacao em Markdown (texto formatado com #titulos, **negrito**, listas).

**`icon-192.png`** _(1 linha)_
Arquivo de imagem.

**`icon-512.png`** _(1 linha)_
Arquivo de imagem.

**`index.html`** _(99 linhas)_
Pagina HTML raiz do projeto. E o ponto de entrada que o browser carrega primeiro.

**`manifest.json`** _(52 linhas)_
Manifesto do PWA — define nome, icone e configuracoes para instalar o app no celular.

**`manual-dev.md`** _(281 linhas)_
Arquivo de documentacao em Markdown (texto formatado com #titulos, **negrito**, listas).

**`opengraph.jpg`** _(1 linha)_
Arquivo de imagem.

**`sw.js`** _(186 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

---

### 📁 `sk-editor/src/components/`
> Pecas visuais reutilizaveis da interface (botoes, cards, formularios...).

**`AIChat.tsx`** _(2339 linhas)_
Componente de CHAT/MENSAGENS — interface de conversa em tempo real.

**`AssistenteJuridico.tsx`** _(1286 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`CampoLivre.tsx`** _(763 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`CodeEditor.tsx`** _(154 linhas)_
Componente EDITOR — area de edicao de texto, codigo ou conteudo rico.

**`CombinarApps.tsx`** _(359 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`DriveBackupPanel.tsx`** _(200 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`EditorLayout.tsx`** _(2713 linhas)_
Componente de LAYOUT — define a estrutura visual da pagina (cabecalho, sidebar, rodape). Envolve outros componentes.

**`FileTree.tsx`** _(400 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`GitHubPanel.tsx`** _(969 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`Manual.tsx`** _(1790 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`PackageSearch.tsx`** _(415 linhas)_
Componente de BUSCA — campo e logica para filtrar/encontrar conteudo.

**`Preview.tsx`** _(496 linhas)_
Componente de PAGINA/TELA — representa uma tela completa navegavel no app.

**`QuickPrompt.tsx`** _(274 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`RealTerminal.tsx`** _(724 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`SKTerminal.tsx`** _(290 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`StreamTerminal.tsx`** _(594 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`SystemStatusPanel.tsx`** _(351 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`TemplateSelector.tsx`** _(589 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`Terminal.tsx`** _(1511 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`VoiceCard.tsx`** _(427 linhas)_
Componente CARD (cartao) — exibe uma informacao em um bloco visual com borda e sombra. Muito usado para listas de items.

**`VoiceMode.tsx`** _(277 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`WebContainerTerminal.tsx`** _(333 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`XTermConnector.tsx`** _(276 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

---

### 📁 `sk-editor/src/hooks/`
> Hooks React customizados — logica reutilizavel de estado e efeitos.

**`use-mobile.tsx`** _(20 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`use-toast.ts`** _(192 linhas)_
HOOK React personalizado para gerenciar estado/comportamento de '-toast'.

---

### 📁 `sk-editor/src/lib/`
> Funcoes auxiliares reutilizaveis em varios lugares do projeto.

**`ai-service.ts`** _(392 linhas)_
Arquivo de SERVICO/API — funcoes para comunicar com o servidor ou API externa.

**`github-service.ts`** _(237 linhas)_
Arquivo de SERVICO/API — funcoes para comunicar com o servidor ou API externa.

**`projects.ts`** _(206 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`store.ts`** _(38 linhas)_
STORE de estado — gerencia o estado global do app (dados compartilhados entre telas).

**`templates.ts`** _(4532 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`tts-service.ts`** _(316 linhas)_
Arquivo de SERVICO/API — funcoes para comunicar com o servidor ou API externa.

**`utils.ts`** _(7 linhas)_
Funcoes UTILITARIAS — ferramentas reutilizaveis de uso geral no projeto.

**`virtual-fs.ts`** _(200 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`zip-service.ts`** _(217 linhas)_
Arquivo de SERVICO/API — funcoes para comunicar com o servidor ou API externa.

---

### 📁 `sk-editor/src/pedaços de outros/`
> Pasta 'pedaços de outros' — agrupamento de arquivos relacionados.

**`ai-panel_1778769976970.tsx`** _(787 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`preview-panel_1778769880659.tsx`** _(588 linhas)_
Componente de PAGINA/TELA — representa uma tela completa navegavel no app.

**`settings_1778769824105.tsx`** _(547 linhas)_
Componente de CONFIGURACOES — tela onde o usuario ajusta preferencias do app.

---

### 📁 `sk-mobile/.expo/types/`
> Definicoes de tipos TypeScript — contratos de dados.

**`router.d.ts`** _(15 linhas)_
Arquivo de ROTAS — define as URLs/enderecos respondidos pelo servidor.

---

### 📁 `sk-mobile/android/app/`
> Pasta 'app' — agrupamento de arquivos relacionados.

**`build.gradle`** _(183 linhas)_
Arquivo GRADLE — parte do projeto.

**`debug.keystore`** _(7 linhas)_
Arquivo KEYSTORE — parte do projeto.

**`proguard-rules.pro`** _(15 linhas)_
Arquivo PRO — parte do projeto.

---

### 📁 `sk-mobile/app/(tabs)/`
> Pasta '(tabs)' — agrupamento de arquivos relacionados.

**`_layout.tsx`** _(162 linhas)_
Componente de LAYOUT — define a estrutura visual da pagina (cabecalho, sidebar, rodape). Envolve outros componentes.

**`clientes.tsx`** _(165 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`configuracoes.tsx`** _(419 linhas)_
Componente de CONFIGURACOES — tela onde o usuario ajusta preferencias do app.

**`iara.tsx`** _(372 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`index.tsx`** _(327 linhas)_
Ponto de entrada do React — monta o componente App na pagina HTML.

**`juridico.tsx`** _(175 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`processos.tsx`** _(167 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

---

### 📁 `sk-mobile/assets/images/`
> Pasta 'images' — agrupamento de arquivos relacionados.

**`icon.png`** _(1 linha)_
Arquivo de imagem.

---

### 📁 `sk-mobile/server/templates/`
> Pasta 'templates' — agrupamento de arquivos relacionados.

**`landing-page.html`** _(461 linhas)_
Arquivo HTML — parte do projeto.

---

### 📁 `apk-builder/dist/public/assets/`
> Arquivos estaticos: imagens, icones, fontes, arquivos publicos.

**`XTermConnector-DkvdoLSY.js`** _(16 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`addon-fit-DX4qG4td.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`addon-web-links-DIbG5aQx.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`index-BayuCH0U.js`** _(492 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`index-DuH2u_vm.css`** _(2 linhas)_
Arquivo de estilos visuais — cores, tamanhos, fontes, espacamentos da interface.

**`xterm-B-qIQCd3.js`** _(17 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

---

### 📁 `apk-builder/src/components/ui/`
> Componentes de UI (interface) basicos e genericos.

**`accordion.tsx`** _(56 linhas)_
Componente ACCORDION — secoes que abrem/fecham ao clicar, economizando espaco na tela.

**`alert-dialog.tsx`** _(140 linhas)_
Componente de NOTIFICACAO/ALERTA — mensagem temporaria que aparece na tela (ex: 'Salvo com sucesso!').

**`alert.tsx`** _(60 linhas)_
Componente de NOTIFICACAO/ALERTA — mensagem temporaria que aparece na tela (ex: 'Salvo com sucesso!').

**`aspect-ratio.tsx`** _(6 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`avatar.tsx`** _(51 linhas)_
Componente AVATAR — foto ou iniciais do usuario em formato circular.

**`badge.tsx`** _(44 linhas)_
Componente BADGE (etiqueta) — pequeno indicador com numero ou status (ex: '3 novas mensagens').

**`breadcrumb.tsx`** _(116 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`button-group.tsx`** _(84 linhas)_
Componente de BOTAO — elemento clicavel reutilizavel com estilo padrao do projeto.

**`button.tsx`** _(66 linhas)_
Componente de BOTAO — elemento clicavel reutilizavel com estilo padrao do projeto.

**`calendar.tsx`** _(214 linhas)_
Componente CALENDARIO/AGENDA — visualizacao e selecao de datas e eventos.

**`card.tsx`** _(77 linhas)_
Componente CARD (cartao) — exibe uma informacao em um bloco visual com borda e sombra. Muito usado para listas de items.

**`carousel.tsx`** _(261 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`chart.tsx`** _(368 linhas)_
Componente de GRAFICO — visualizacao de dados em forma de grafico (barras, linhas, pizza...).

**`checkbox.tsx`** _(29 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`collapsible.tsx`** _(12 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`command.tsx`** _(154 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`context-menu.tsx`** _(199 linhas)_
CONTEXT do React — mecanismo para compartilhar dados entre componentes sem passar por props.

**`dialog.tsx`** _(121 linhas)_
Componente DIALOG — caixa de dialogo que exige resposta do usuario (confirmar, cancelar...).

**`drawer.tsx`** _(117 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`dropdown-menu.tsx`** _(202 linhas)_
Componente de MENU/DROPDOWN — lista de opcoes que aparece ao clicar em um botao.

**`empty.tsx`** _(105 linhas)_
Componente de ESTADO VAZIO — exibido quando nao ha dados para mostrar (ex: 'Nenhum resultado encontrado').

**`field.tsx`** _(245 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`form.tsx`** _(177 linhas)_
Componente de FORMULARIO — campos de entrada de dados (texto, selecao, etc.) com validacao.

**`hover-card.tsx`** _(28 linhas)_
Componente CARD (cartao) — exibe uma informacao em um bloco visual com borda e sombra. Muito usado para listas de items.

**`input-group.tsx`** _(169 linhas)_
Componente de CAMPO DE ENTRADA — elemento de input com estilo personalizado.

**`input-otp.tsx`** _(70 linhas)_
Componente de CAMPO DE ENTRADA — elemento de input com estilo personalizado.

**`input.tsx`** _(23 linhas)_
Componente de CAMPO DE ENTRADA — elemento de input com estilo personalizado.

**`item.tsx`** _(194 linhas)_
Componente de ITEM — representa um elemento individual dentro de uma lista ou colecao.

**`kbd.tsx`** _(29 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`label.tsx`** _(27 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`menubar.tsx`** _(255 linhas)_
Componente de MENU/DROPDOWN — lista de opcoes que aparece ao clicar em um botao.

**`navigation-menu.tsx`** _(129 linhas)_
Componente de NAVEGACAO/CABECALHO — barra superior com logo, menu e links de navegacao.

**`pagination.tsx`** _(118 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`popover.tsx`** _(32 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`progress.tsx`** _(29 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`radio-group.tsx`** _(43 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`resizable.tsx`** _(46 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`scroll-area.tsx`** _(47 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`select.tsx`** _(160 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`separator.tsx`** _(30 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`sheet.tsx`** _(141 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`sidebar.tsx`** _(728 linhas)_
Componente de BARRA LATERAL — menu ou painel que aparece na lateral da tela.

**`skeleton.tsx`** _(16 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`slider.tsx`** _(27 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`sonner.tsx`** _(32 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`spinner.tsx`** _(17 linhas)_
Componente de CARREGAMENTO — animacao visual que aparece enquanto dados estao sendo buscados.

**`switch.tsx`** _(28 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`table.tsx`** _(121 linhas)_
Componente de TABELA — exibe dados em linhas e colunas.

**`tabs.tsx`** _(54 linhas)_
Componente de ABAS — permite alternar entre diferentes secoes de conteudo com clique.

**`textarea.tsx`** _(23 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`toast.tsx`** _(128 linhas)_
Componente de NOTIFICACAO/ALERTA — mensagem temporaria que aparece na tela (ex: 'Salvo com sucesso!').

**`toaster.tsx`** _(34 linhas)_
Componente de NOTIFICACAO/ALERTA — mensagem temporaria que aparece na tela (ex: 'Salvo com sucesso!').

**`toggle-group.tsx`** _(62 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`toggle.tsx`** _(44 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`tooltip.tsx`** _(33 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

---

### 📁 `assistente-juridico/android/.gradle/8.14.3/`
> Pasta '8.14.3' — agrupamento de arquivos relacionados.

**`gc.properties`** _(1 linha)_
Arquivo PROPERTIES — parte do projeto.

---

### 📁 `assistente-juridico/android/.gradle/buildOutputCleanup/`
> Pasta 'buildOutputCleanup' — agrupamento de arquivos relacionados.

**`buildOutputCleanup.lock`** _(1 linha)_
Arquivo LOCK — parte do projeto.

**`cache.properties`** _(3 linhas)_
Arquivo PROPERTIES — parte do projeto.

**`outputFiles.bin`** _(1 linha)_
Arquivo BIN — parte do projeto.

---

### 📁 `assistente-juridico/android/.gradle/vcs-1/`
> Pasta 'vcs-1' — agrupamento de arquivos relacionados.

**`gc.properties`** _(1 linha)_
Arquivo PROPERTIES — parte do projeto.

---

### 📁 `assistente-juridico/dist/public/assets/`
> Arquivos estaticos: imagens, icones, fontes, arquivos publicos.

**`admin-CBkE_xRa.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`arrow-left-De2M_wPP.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`assinatura-BxGVlQr8.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`badge-DvsEBxZE.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`bell-BAx4uqwM.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`book-open-C60h3AJh.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`bot-CQEA4oRY.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`building-2-BXpbgOaa.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`button-BUGwJ1r4.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`calendar-Bn-2Hr63.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`card-mbB_popU.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`check-efW8jyn0.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`chevron-down-r3_9_CMA.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`chevron-left-BLKLetW2.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`chevron-right-BzsbPMa4.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`chevron-up-KuwEdWNQ.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`circle-DjYp1w7I.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`circle-alert-eSv2vETe.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`circle-check-B6Hbs4xE.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`circle-x-gjVK4Jgn.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`clock-C4R428W7.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`codigo-DICocSqs.js`** _(9 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`colaborativo-CCSq-6n3.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`comparador-juridico-349a-1z6.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`comunicacoes-cnj-Bz91U-FP.js`** _(9 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`configuracoes-Ct8H_2FW.js`** _(3 linhas)_
Arquivo de CONSTANTES/CONFIGURACAO — valores fixos usados em varios lugares do projeto.

**`consulta-corporativo-DM1UUrc5.js`** _(5 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`consulta-pdpj-3DTOMKnM.js`** _(2 linhas)_
Arquivo de TIPOS — define as estruturas de dados (interfaces TypeScript) usadas no projeto.

**`consulta-processual-Cw2Gu7NA.js`** _(13 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`copy-BFLCPv5x.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`cpu-C024Qcuy.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`database-DLAbLVck.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`dialog-BAg_0Wok.js`** _(6 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`download-DuwWgM3Q.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`ementas-CJZty0Wh.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`escritorio-BLm-INPe.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`external-link-BxUuqUaE.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`eye-GP31qHS-.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`eye-off-CnZx4Rv_.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`file-text-Bv5C0iRI.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`filtrador-ChgRMOq6.js`** _(40 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`gavel-BJpPYw1K.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`historico-oQEcg4nM.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`history-2mjGnPtq.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`index-39mgIYgx.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`index-AUXLjOsf.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`index-BVE5xndR.js`** _(222 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`index-BdQq_4o_.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`index-DOQDzLwe.js`** _(42 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`index-DOpuvYws.css`** _(2 linhas)_
Arquivo de estilos visuais — cores, tamanhos, fontes, espacamentos da interface.

**`index-Dju8vJgD.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`index-MfVsal_x.js`** _(11 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`info-CTTXh9QD.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`input-LSRw2cwy.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`jurisprudencia-B2y-dTXc.js`** _(75 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`key-BBkVXwEW.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`label-OX8Mn1-0.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`legal-assistant-A7mZ5Kt6.js`** _(115 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`log-out-Bw9EOYRA.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`login-Dzsw5OEx.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`mail-BNiJ5jWe.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`message-square-0jM2-GKg.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`not-found-Dpb2K0qk.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`painel-processos-CcOi2au5.js`** _(13 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`pdf-B75MOh95.js`** _(56 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`pencil-DBnBVZSc.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`pje-mlPLPa45.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`play-Dk83ynRF.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`playground-CZrotIxo.js`** _(390 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`plus-Du7Lo3bz.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`prazos-Pg0PZw65.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`refresh-cw-GPND3eQm.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`robo-djen-Ix2S-0G6.js`** _(5 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`rotate-ccw-Cg5i5ug3.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`save-DOpTQH4r.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`scale-BfcSY8rh.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`search-rmZIdwX6.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`select-Bnqk4twF.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`separator-D_rvx2CS.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`server-DbDCGMHt.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`settings-BCCdn6tP.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`shield-BaXcWJi9.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`slider-CiGH8XhB.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`status-CQbd-8UQ.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`tabs-BgH_zz7Z.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`tag-BHLeQaPL.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`target-BD3QZD5M.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`templates-juridicos-1ZiNvz08.js`** _(646 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`terminal-DjCaBnXe.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`textarea-CW5o07-G.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`theme-toggle-DxQ7IR8r.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`tiptap-editor-CMlHrtsu.js`** _(154 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`token-generator-BGC3zoEJ.js`** _(27 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`tramitacao-DsUHMM8Q.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`trash-2-DEBfAqIY.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`triangle-alert-B4YV2-Gk.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`upload-Cj7-ngfC.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`useMutation-BJ86liox.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`user-B9hczYUr.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`user-check-DrvS6C4f.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`users-DB2QB59g.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`volume-x-CTBNzjlm.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`wifi-off-CbHSy9GE.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`zap-B2kCwK0T.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

---

### 📁 `juridico/dist/public/assets/`
> Arquivos estaticos: imagens, icones, fontes, arquivos publicos.

**`admin-CSYibXzg.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`arrow-left-DBwtgAcy.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`assinatura-CpoFU8iN.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`audio-lines-DsBMIcUK.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`auditoria-financeira-BTiZ_MnQ.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`badge-CD7rZS7n.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`bell-Cht0EACw.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`book-open-BKWsciMp.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`bot-CpPmyCuP.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`briefcase-B5MNLBsd.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`building-2-CEkB_bNa.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`button-DmWEFtXm.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`calendar-wAE2F37_.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`card-BipkLjeB.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`check-BnLyF3Wu.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`chevron-down-C8pb4oN1.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`chevron-left-CCCXiGGa.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`chevron-right-D1ryeHHM.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`chevron-up-Cge-G70_.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`circle-BASCHiMY.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`circle-alert-nMBd91WP.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`circle-check-CM4Qdbnm.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`circle-stop-C2ikIssX.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`circle-x-qu7znTBo.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`clock-BbEb8j2V.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`codigo-CcBp48WS.js`** _(9 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`colaborativo-D6VQuPIO.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`comparador-juridico-Cliqnr15.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`comunicacoes-cnj-BeEOY83h.js`** _(9 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`configuracoes-BSFwYNAK.js`** _(3 linhas)_
Arquivo de CONSTANTES/CONFIGURACAO — valores fixos usados em varios lugares do projeto.

**`consulta-corporativo-BWNqd6Yg.js`** _(5 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`consulta-pdpj-CF1e66rQ.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`consulta-processual-DDmG4iSv.js`** _(13 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`copy-C7yzOVrI.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`cpu-BYm_2wvI.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`database-Dllzk6br.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`dialog-C_UTeQ-Z.js`** _(6 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`download-DnUulWCg.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`ementas-AisZ7hh-.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`escritorio-DlPQALZe.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`external-link-BgiAxW7g.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`eye-off-DNQQfmQu.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`eye-sSfRAZ3B.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`file-text-DeLlVhKq.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`fileExtract-DHdlQI-A.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`filtrador-cyiDAYMn.js`** _(40 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`folder-open-Hodf7wN5.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`gavel-B06xpq47.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`globe-DuhDY7M0.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`guia-C7Wlu1qL.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`hash-Bw4xy2Sx.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`historico-CLCC7I0D.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`history-ByeCVPNp.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`iara-Bd1pWhht.js`** _(90 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`index-28kpihTt.js`** _(42 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`index-B0YTb96v.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`index-BdQq_4o_.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`index-C024M3US.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`index-CV6QfelB.css`** _(2 linhas)_
Arquivo de estilos visuais — cores, tamanhos, fontes, espacamentos da interface.

**`index-CyxGmtCR.js`** _(222 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`index-_XSsFKKV.js`** _(14 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`index-odkcds6s.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`info-C5AUWl9g.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`input-Beq58fdb.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`juridico-pro-BWCnCh2d.js`** _(81 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`jurisprudencia-DvzR4k6L.js`** _(75 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`key-CTaoIv58.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`label-HELNMd2g.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`legal-assistant-7f5CZd36.js`** _(113 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`log-out-BeBgRdd1.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`login-CE_5BhYm.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`mail-BPCTbTIi.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`message-square-BIdD7JRM.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`not-found-GHY-j2Fl.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`painel-processos-e5eYYiY3.js`** _(13 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`pdf-B75MOh95.js`** _(56 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`pencil-h4X763Lf.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`pje-0rVw9OtK.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`play-LyUojDBq.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`playground-C0OXxrnU.js`** _(390 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`plus-CD9lH7pR.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`prazos-Ca2drPlS.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`previdenciario-CHmA8mVg.js`** _(10 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`refresh-cw-DLZ40eiX.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`robo-djen-DaDoUMvg.js`** _(5 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`rotate-ccw-BDKSv7NN.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`save-BtYt8O-3.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`scale-DL44_Z-P.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`search-CUEuJlJo.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`select-BaIKZQjg.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`separator-K4xwL5Pb.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`server-YwLnhmJu.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`settings-CdQsakcp.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`shield-vDD54pHO.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`slider-Dzf2vR38.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`status--LNis53d.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`tabs-Bxm6G3dy.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`tag-LbJW7TIK.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`target-BZCQz0Bh.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`templates-juridicos-Cwfg0dU9.js`** _(646 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`terminal-BUZM54jF.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`textarea-_aV9rgWP.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`theme-toggle-BCfIU4lM.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`tiptap-editor-BJcziLjr.js`** _(154 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`token-generator-ZC4hDR0T.js`** _(27 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`tramitacao-Mzn2xBf9.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`trash-2-Cy2W2HFq.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`triangle-alert-DOLme-hg.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`upload-Mpfhr3q3.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`useMutation-CYMlB8dT.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`user-A83hgMSo.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`user-check-KjU15eFV.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`users-Do3AZQrD.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`volume-2-Bp1t5cX0.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`volume-x-DAyhgBMg.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`wifi-BFhgqE2o.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`zap-CyosTu31.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

---

### 📁 `juridico/dist/public/icons/`
> Icones do projeto.

**`icon-128x128.svg`** _(8 linhas)_
Imagem vetorial (icone ou ilustracao que nao perde qualidade ao ampliar).

**`icon-144x144.svg`** _(8 linhas)_
Imagem vetorial (icone ou ilustracao que nao perde qualidade ao ampliar).

**`icon-152x152.svg`** _(8 linhas)_
Imagem vetorial (icone ou ilustracao que nao perde qualidade ao ampliar).

**`icon-192x192.svg`** _(8 linhas)_
Imagem vetorial (icone ou ilustracao que nao perde qualidade ao ampliar).

**`icon-384x384.svg`** _(8 linhas)_
Imagem vetorial (icone ou ilustracao que nao perde qualidade ao ampliar).

**`icon-512x512.svg`** _(8 linhas)_
Imagem vetorial (icone ou ilustracao que nao perde qualidade ao ampliar).

**`icon-72x72.svg`** _(8 linhas)_
Imagem vetorial (icone ou ilustracao que nao perde qualidade ao ampliar).

**`icon-96x96.svg`** _(8 linhas)_
Imagem vetorial (icone ou ilustracao que nao perde qualidade ao ampliar).

---

### 📁 `juridico/src/components/ui/`
> Componentes de UI (interface) basicos e genericos.

**`accordion.tsx`** _(56 linhas)_
Componente ACCORDION — secoes que abrem/fecham ao clicar, economizando espaco na tela.

**`alert-dialog.tsx`** _(140 linhas)_
Componente de NOTIFICACAO/ALERTA — mensagem temporaria que aparece na tela (ex: 'Salvo com sucesso!').

**`alert.tsx`** _(60 linhas)_
Componente de NOTIFICACAO/ALERTA — mensagem temporaria que aparece na tela (ex: 'Salvo com sucesso!').

**`aspect-ratio.tsx`** _(6 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`avatar.tsx`** _(51 linhas)_
Componente AVATAR — foto ou iniciais do usuario em formato circular.

**`badge.tsx`** _(38 linhas)_
Componente BADGE (etiqueta) — pequeno indicador com numero ou status (ex: '3 novas mensagens').

**`breadcrumb.tsx`** _(116 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`button-group.tsx`** _(84 linhas)_
Componente de BOTAO — elemento clicavel reutilizavel com estilo padrao do projeto.

**`button.tsx`** _(59 linhas)_
Componente de BOTAO — elemento clicavel reutilizavel com estilo padrao do projeto.

**`calendar.tsx`** _(214 linhas)_
Componente CALENDARIO/AGENDA — visualizacao e selecao de datas e eventos.

**`card.tsx`** _(77 linhas)_
Componente CARD (cartao) — exibe uma informacao em um bloco visual com borda e sombra. Muito usado para listas de items.

**`carousel.tsx`** _(261 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`chart.tsx`** _(368 linhas)_
Componente de GRAFICO — visualizacao de dados em forma de grafico (barras, linhas, pizza...).

**`checkbox.tsx`** _(29 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`collapsible.tsx`** _(12 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`command.tsx`** _(154 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`context-menu.tsx`** _(199 linhas)_
CONTEXT do React — mecanismo para compartilhar dados entre componentes sem passar por props.

**`dialog.tsx`** _(121 linhas)_
Componente DIALOG — caixa de dialogo que exige resposta do usuario (confirmar, cancelar...).

**`drawer.tsx`** _(117 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`dropdown-menu.tsx`** _(202 linhas)_
Componente de MENU/DROPDOWN — lista de opcoes que aparece ao clicar em um botao.

**`empty.tsx`** _(105 linhas)_
Componente de ESTADO VAZIO — exibido quando nao ha dados para mostrar (ex: 'Nenhum resultado encontrado').

**`field.tsx`** _(245 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`form.tsx`** _(177 linhas)_
Componente de FORMULARIO — campos de entrada de dados (texto, selecao, etc.) com validacao.

**`hover-card.tsx`** _(28 linhas)_
Componente CARD (cartao) — exibe uma informacao em um bloco visual com borda e sombra. Muito usado para listas de items.

**`input-group.tsx`** _(169 linhas)_
Componente de CAMPO DE ENTRADA — elemento de input com estilo personalizado.

**`input-otp.tsx`** _(70 linhas)_
Componente de CAMPO DE ENTRADA — elemento de input com estilo personalizado.

**`input.tsx`** _(23 linhas)_
Componente de CAMPO DE ENTRADA — elemento de input com estilo personalizado.

**`item.tsx`** _(194 linhas)_
Componente de ITEM — representa um elemento individual dentro de uma lista ou colecao.

**`kbd.tsx`** _(29 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`label.tsx`** _(27 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`menubar.tsx`** _(255 linhas)_
Componente de MENU/DROPDOWN — lista de opcoes que aparece ao clicar em um botao.

**`navigation-menu.tsx`** _(129 linhas)_
Componente de NAVEGACAO/CABECALHO — barra superior com logo, menu e links de navegacao.

**`pagination.tsx`** _(118 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`popover.tsx`** _(32 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`progress.tsx`** _(29 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`radio-group.tsx`** _(43 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`resizable.tsx`** _(46 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`scroll-area.tsx`** _(47 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`select.tsx`** _(160 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`separator.tsx`** _(30 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`sheet.tsx`** _(141 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`sidebar.tsx`** _(728 linhas)_
Componente de BARRA LATERAL — menu ou painel que aparece na lateral da tela.

**`skeleton.tsx`** _(16 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`slider.tsx`** _(27 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`sonner.tsx`** _(32 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`spinner.tsx`** _(17 linhas)_
Componente de CARREGAMENTO — animacao visual que aparece enquanto dados estao sendo buscados.

**`switch.tsx`** _(28 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`table.tsx`** _(121 linhas)_
Componente de TABELA — exibe dados em linhas e colunas.

**`tabs.tsx`** _(54 linhas)_
Componente de ABAS — permite alternar entre diferentes secoes de conteudo com clique.

**`textarea.tsx`** _(23 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`toast.tsx`** _(128 linhas)_
Componente de NOTIFICACAO/ALERTA — mensagem temporaria que aparece na tela (ex: 'Salvo com sucesso!').

**`toaster.tsx`** _(34 linhas)_
Componente de NOTIFICACAO/ALERTA — mensagem temporaria que aparece na tela (ex: 'Salvo com sucesso!').

**`toggle-group.tsx`** _(62 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`toggle.tsx`** _(44 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`tooltip.tsx`** _(33 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

---

### 📁 `sk-editor/dist/public/assets/`
> Arquivos estaticos: imagens, icones, fontes, arquivos publicos.

**`XTermConnector-udiVE6cg.js`** _(16 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`addon-fit-DX4qG4td.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`addon-web-links-DIbG5aQx.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`index-Cg47B_PG.css`** _(2 linhas)_
Arquivo de estilos visuais — cores, tamanhos, fontes, espacamentos da interface.

**`index-Dn05cZXz.js`** _(6009 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`xterm-B-qIQCd3.js`** _(17 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

---

### 📁 `sk-editor/src/components/ui/`
> Componentes de UI (interface) basicos e genericos.

**`accordion.tsx`** _(56 linhas)_
Componente ACCORDION — secoes que abrem/fecham ao clicar, economizando espaco na tela.

**`alert-dialog.tsx`** _(140 linhas)_
Componente de NOTIFICACAO/ALERTA — mensagem temporaria que aparece na tela (ex: 'Salvo com sucesso!').

**`alert.tsx`** _(60 linhas)_
Componente de NOTIFICACAO/ALERTA — mensagem temporaria que aparece na tela (ex: 'Salvo com sucesso!').

**`aspect-ratio.tsx`** _(6 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`avatar.tsx`** _(51 linhas)_
Componente AVATAR — foto ou iniciais do usuario em formato circular.

**`badge.tsx`** _(44 linhas)_
Componente BADGE (etiqueta) — pequeno indicador com numero ou status (ex: '3 novas mensagens').

**`breadcrumb.tsx`** _(116 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`button-group.tsx`** _(84 linhas)_
Componente de BOTAO — elemento clicavel reutilizavel com estilo padrao do projeto.

**`button.tsx`** _(66 linhas)_
Componente de BOTAO — elemento clicavel reutilizavel com estilo padrao do projeto.

**`calendar.tsx`** _(214 linhas)_
Componente CALENDARIO/AGENDA — visualizacao e selecao de datas e eventos.

**`card.tsx`** _(77 linhas)_
Componente CARD (cartao) — exibe uma informacao em um bloco visual com borda e sombra. Muito usado para listas de items.

**`carousel.tsx`** _(261 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`chart.tsx`** _(368 linhas)_
Componente de GRAFICO — visualizacao de dados em forma de grafico (barras, linhas, pizza...).

**`checkbox.tsx`** _(29 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`collapsible.tsx`** _(12 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`command.tsx`** _(154 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`context-menu.tsx`** _(199 linhas)_
CONTEXT do React — mecanismo para compartilhar dados entre componentes sem passar por props.

**`dialog.tsx`** _(121 linhas)_
Componente DIALOG — caixa de dialogo que exige resposta do usuario (confirmar, cancelar...).

**`drawer.tsx`** _(117 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`dropdown-menu.tsx`** _(202 linhas)_
Componente de MENU/DROPDOWN — lista de opcoes que aparece ao clicar em um botao.

**`empty.tsx`** _(105 linhas)_
Componente de ESTADO VAZIO — exibido quando nao ha dados para mostrar (ex: 'Nenhum resultado encontrado').

**`field.tsx`** _(245 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`form.tsx`** _(177 linhas)_
Componente de FORMULARIO — campos de entrada de dados (texto, selecao, etc.) com validacao.

**`hover-card.tsx`** _(28 linhas)_
Componente CARD (cartao) — exibe uma informacao em um bloco visual com borda e sombra. Muito usado para listas de items.

**`input-group.tsx`** _(169 linhas)_
Componente de CAMPO DE ENTRADA — elemento de input com estilo personalizado.

**`input-otp.tsx`** _(70 linhas)_
Componente de CAMPO DE ENTRADA — elemento de input com estilo personalizado.

**`input.tsx`** _(23 linhas)_
Componente de CAMPO DE ENTRADA — elemento de input com estilo personalizado.

**`item.tsx`** _(194 linhas)_
Componente de ITEM — representa um elemento individual dentro de uma lista ou colecao.

**`kbd.tsx`** _(29 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`label.tsx`** _(27 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`menubar.tsx`** _(255 linhas)_
Componente de MENU/DROPDOWN — lista de opcoes que aparece ao clicar em um botao.

**`navigation-menu.tsx`** _(129 linhas)_
Componente de NAVEGACAO/CABECALHO — barra superior com logo, menu e links de navegacao.

**`pagination.tsx`** _(118 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`popover.tsx`** _(32 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`progress.tsx`** _(29 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`radio-group.tsx`** _(43 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`resizable.tsx`** _(46 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`scroll-area.tsx`** _(47 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`select.tsx`** _(160 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`separator.tsx`** _(30 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`sheet.tsx`** _(141 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`sidebar.tsx`** _(728 linhas)_
Componente de BARRA LATERAL — menu ou painel que aparece na lateral da tela.

**`skeleton.tsx`** _(16 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`slider.tsx`** _(27 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`sonner.tsx`** _(32 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`spinner.tsx`** _(17 linhas)_
Componente de CARREGAMENTO — animacao visual que aparece enquanto dados estao sendo buscados.

**`switch.tsx`** _(28 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`table.tsx`** _(121 linhas)_
Componente de TABELA — exibe dados em linhas e colunas.

**`tabs.tsx`** _(54 linhas)_
Componente de ABAS — permite alternar entre diferentes secoes de conteudo com clique.

**`textarea.tsx`** _(23 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`toast.tsx`** _(128 linhas)_
Componente de NOTIFICACAO/ALERTA — mensagem temporaria que aparece na tela (ex: 'Salvo com sucesso!').

**`toaster.tsx`** _(34 linhas)_
Componente de NOTIFICACAO/ALERTA — mensagem temporaria que aparece na tela (ex: 'Salvo com sucesso!').

**`toggle-group.tsx`** _(62 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`toggle.tsx`** _(44 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`tooltip.tsx`** _(33 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

---

### 📁 `sk-mobile/android/.gradle/buildOutputCleanup/`
> Pasta 'buildOutputCleanup' — agrupamento de arquivos relacionados.

**`buildOutputCleanup.lock`** _(1 linha)_
Arquivo LOCK — parte do projeto.

**`cache.properties`** _(3 linhas)_
Arquivo PROPERTIES — parte do projeto.

---

### 📁 `sk-mobile/android/gradle/wrapper/`
> Pasta 'wrapper' — agrupamento de arquivos relacionados.

**`gradle-wrapper.jar`** _(1 linha)_
Arquivo JAR — parte do projeto.

**`gradle-wrapper.properties`** _(8 linhas)_
Arquivo PROPERTIES — parte do projeto.

---

### 📁 `assistente-juridico/android/.gradle/8.14.3/checksums/`
> Pasta 'checksums' — agrupamento de arquivos relacionados.

**`checksums.lock`** _(1 linha)_
Arquivo LOCK — parte do projeto.

**`md5-checksums.bin`** _(1 linha)_
Arquivo BIN — parte do projeto.

**`sha1-checksums.bin`** _(1 linha)_
Arquivo BIN — parte do projeto.

---

### 📁 `assistente-juridico/android/.gradle/8.14.3/executionHistory/`
> Pasta 'executionHistory' — agrupamento de arquivos relacionados.

**`executionHistory.bin`** _(1 linha)_
Arquivo BIN — parte do projeto.

**`executionHistory.lock`** _(1 linha)_
Arquivo LOCK — parte do projeto.

---

### 📁 `assistente-juridico/android/.gradle/8.14.3/fileChanges/`
> Pasta 'fileChanges' — agrupamento de arquivos relacionados.

**`last-build.bin`** _(1 linha)_
Arquivo BIN — parte do projeto.

---

### 📁 `assistente-juridico/android/.gradle/8.14.3/fileHashes/`
> Pasta 'fileHashes' — agrupamento de arquivos relacionados.

**`fileHashes.bin`** _(1 linha)_
Arquivo BIN — parte do projeto.

**`fileHashes.lock`** _(1 linha)_
Arquivo LOCK — parte do projeto.

**`resourceHashesCache.bin`** _(1 linha)_
Arquivo BIN — parte do projeto.

---

### 📁 `assistente-juridico/android/capacitor-cordova-android-plugins/src/main/`
> Pasta 'main' — agrupamento de arquivos relacionados.

**`AndroidManifest.xml`** _(8 linhas)_
Arquivo XML — parte do projeto.

---

### 📁 `sk-mobile/android/.gradle/8.14.3/checksums/`
> Pasta 'checksums' — agrupamento de arquivos relacionados.

**`checksums.lock`** _(1 linha)_
Arquivo LOCK — parte do projeto.

**`md5-checksums.bin`** _(1 linha)_
Arquivo BIN — parte do projeto.

**`sha1-checksums.bin`** _(1 linha)_
Arquivo BIN — parte do projeto.

---

### 📁 `sk-mobile/android/.gradle/8.14.3/fileHashes/`
> Pasta 'fileHashes' — agrupamento de arquivos relacionados.

**`fileHashes.lock`** _(1 linha)_
Arquivo LOCK — parte do projeto.

---

### 📁 `sk-mobile/android/app/src/debug/`
> Pasta 'debug' — agrupamento de arquivos relacionados.

**`AndroidManifest.xml`** _(8 linhas)_
Arquivo XML — parte do projeto.

---

### 📁 `sk-mobile/android/app/src/debugOptimized/`
> Pasta 'debugOptimized' — agrupamento de arquivos relacionados.

**`AndroidManifest.xml`** _(8 linhas)_
Arquivo XML — parte do projeto.

---

### 📁 `sk-mobile/android/app/src/main/`
> Pasta 'main' — agrupamento de arquivos relacionados.

**`AndroidManifest.xml`** _(34 linhas)_
Arquivo XML — parte do projeto.

---

### 📁 `assistente-juridico/android/app/src/main/assets/`
> Arquivos estaticos: imagens, icones, fontes, arquivos publicos.

**`capacitor.config.json`** _(20 linhas)_
Arquivo de dados ou configuracao no formato JSON (chave: valor).

**`capacitor.plugins.json`** _(2 linhas)_
Arquivo de dados ou configuracao no formato JSON (chave: valor).

---

### 📁 `assistente-juridico/android/capacitor-cordova-android-plugins/src/main/java/`
> Pasta 'java' — agrupamento de arquivos relacionados.

**`.gitkeep`** _(1 linha)_
Arquivo GITKEEP — parte do projeto.

---

### 📁 `assistente-juridico/android/capacitor-cordova-android-plugins/src/main/res/`
> Pasta 'res' — agrupamento de arquivos relacionados.

**`.gitkeep`** _(2 linhas)_
Arquivo GITKEEP — parte do projeto.

---

### 📁 `assistente-juridico/android/app/src/main/assets/public/`
> Arquivos estaticos: imagens, icones, fontes, arquivos publicos.

**`SK-Juridico-IA.apk`** _(1 linha)_
Arquivo APK — parte do projeto.

**`cordova.js`** _(1 linha)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`cordova_plugins.js`** _(1 linha)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`favicon.svg`** _(4 linhas)_
Imagem vetorial (icone ou ilustracao que nao perde qualidade ao ampliar).

**`icon-192.png`** _(1 linha)_
Arquivo de imagem.

**`icon-384.png`** _(1 linha)_
Arquivo de imagem.

**`icon-512.png`** _(1 linha)_
Arquivo de imagem.

**`icon-96.png`** _(1 linha)_
Arquivo de imagem.

**`index.html`** _(54 linhas)_
Pagina HTML raiz do projeto. E o ponto de entrada que o browser carrega primeiro.

**`manifest.json`** _(64 linhas)_
Manifesto do PWA — define nome, icone e configuracoes para instalar o app no celular.

**`opengraph.jpg`** _(1 linha)_
Arquivo de imagem.

**`robots.txt`** _(3 linhas)_
Arquivo TXT — parte do projeto.

**`sw.js`** _(202 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

---

### 📁 `assistente-juridico/android/app/src/main/res/xml/`
> Pasta 'xml' — agrupamento de arquivos relacionados.

**`config.xml`** _(6 linhas)_
Arquivo XML — parte do projeto.

---

### 📁 `sk-mobile/android/app/src/main/res/drawable/`
> Pasta 'drawable' — agrupamento de arquivos relacionados.

**`ic_launcher_background.xml`** _(6 linhas)_
Arquivo XML — parte do projeto.

**`rn_edit_text_material.xml`** _(38 linhas)_
Arquivo XML — parte do projeto.

---

### 📁 `sk-mobile/android/app/src/main/res/drawable-hdpi/`
> Pasta 'drawable-hdpi' — agrupamento de arquivos relacionados.

**`splashscreen_logo.png`** _(1 linha)_
Arquivo de imagem.

---

### 📁 `sk-mobile/android/app/src/main/res/drawable-mdpi/`
> Pasta 'drawable-mdpi' — agrupamento de arquivos relacionados.

**`splashscreen_logo.png`** _(1 linha)_
Arquivo de imagem.

---

### 📁 `sk-mobile/android/app/src/main/res/drawable-xhdpi/`
> Pasta 'drawable-xhdpi' — agrupamento de arquivos relacionados.

**`splashscreen_logo.png`** _(1 linha)_
Arquivo de imagem.

---

### 📁 `sk-mobile/android/app/src/main/res/drawable-xxhdpi/`
> Pasta 'drawable-xxhdpi' — agrupamento de arquivos relacionados.

**`splashscreen_logo.png`** _(1 linha)_
Arquivo de imagem.

---

### 📁 `sk-mobile/android/app/src/main/res/drawable-xxxhdpi/`
> Pasta 'drawable-xxxhdpi' — agrupamento de arquivos relacionados.

**`splashscreen_logo.png`** _(1 linha)_
Arquivo de imagem.

---

### 📁 `sk-mobile/android/app/src/main/res/mipmap-hdpi/`
> Pasta 'mipmap-hdpi' — agrupamento de arquivos relacionados.

**`ic_launcher.webp`** _(1 linha)_
Arquivo de imagem.

**`ic_launcher_foreground.webp`** _(1 linha)_
Arquivo de imagem.

---

### 📁 `sk-mobile/android/app/src/main/res/mipmap-mdpi/`
> Pasta 'mipmap-mdpi' — agrupamento de arquivos relacionados.

**`ic_launcher.webp`** _(1 linha)_
Arquivo de imagem.

**`ic_launcher_foreground.webp`** _(1 linha)_
Arquivo de imagem.

---

### 📁 `sk-mobile/android/app/src/main/res/mipmap-xhdpi/`
> Pasta 'mipmap-xhdpi' — agrupamento de arquivos relacionados.

**`ic_launcher.webp`** _(1 linha)_
Arquivo de imagem.

**`ic_launcher_foreground.webp`** _(1 linha)_
Arquivo de imagem.

---

### 📁 `sk-mobile/android/app/src/main/res/mipmap-xxhdpi/`
> Pasta 'mipmap-xxhdpi' — agrupamento de arquivos relacionados.

**`ic_launcher.webp`** _(1 linha)_
Arquivo de imagem.

**`ic_launcher_foreground.webp`** _(1 linha)_
Arquivo de imagem.

---

### 📁 `sk-mobile/android/app/src/main/res/mipmap-xxxhdpi/`
> Pasta 'mipmap-xxxhdpi' — agrupamento de arquivos relacionados.

**`ic_launcher.webp`** _(1 linha)_
Arquivo de imagem.

**`ic_launcher_foreground.webp`** _(1 linha)_
Arquivo de imagem.

---

### 📁 `sk-mobile/android/app/src/main/res/values/`
> Pasta 'values' — agrupamento de arquivos relacionados.

**`colors.xml`** _(6 linhas)_
Arquivo XML — parte do projeto.

**`strings.xml`** _(6 linhas)_
Arquivo XML — parte do projeto.

**`styles.xml`** _(14 linhas)_
Arquivo XML — parte do projeto.

---

### 📁 `sk-mobile/android/app/src/main/res/values-night/`
> Pasta 'values-night' — agrupamento de arquivos relacionados.

**`colors.xml`** _(1 linha)_
Arquivo XML — parte do projeto.

---

### 📁 `assistente-juridico/android/app/src/main/assets/public/assets/`
> Arquivos estaticos: imagens, icones, fontes, arquivos publicos.

**`admin-wZRLZyDy.js`** _(12 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`arrow-left-DYElIYXR.js`** _(7 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`assinatura-BHt3Qvse.js`** _(7 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`auditoria-financeira-C-CiXcAZ.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`badge-BCXvIIul.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`bell-B5W5rjOr.js`** _(7 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`book-open-CctBA1uj.js`** _(7 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`bot-B-04Xe7b.js`** _(7 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`briefcase-jFpqll2q.js`** _(7 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`building-2-ywDJkoHl.js`** _(7 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`button-D5ZhSwEd.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`calendar-B664tU9C.js`** _(7 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`card-BtrX4egs.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`check-CwxI4-xR.js`** _(7 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`chevron-down-uth5WLjM.js`** _(7 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`chevron-left-BRbXarL_.js`** _(7 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`chevron-right-CedePU1E.js`** _(7 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`chevron-up-C9iGwLbl.js`** _(7 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`circle-CG12gPnc.js`** _(7 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`circle-alert-DPHqLNmk.js`** _(7 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`circle-x-CwgzW83o.js`** _(7 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`clock-D9M-tegz.js`** _(7 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`codigo-CFUnhIfo.js`** _(19 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`colaborativo-COD6aFte.js`** _(12 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`comparador-juridico-DYsbk112.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`comunicacoes-cnj-CJy6IPR8.js`** _(9 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`configuracoes-BuhDceYz.js`** _(48 linhas)_
Arquivo de CONSTANTES/CONFIGURACAO — valores fixos usados em varios lugares do projeto.

**`consulta-corporativo-BSKcbntC.js`** _(10 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`consulta-pdpj-BtJMr5YB.js`** _(7 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`consulta-processual-CS_HcDnj.js`** _(13 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`copy-C0ymX2fa.js`** _(7 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`cpu-z3we3BDw.js`** _(7 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`database-CYrcrLbK.js`** _(7 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`dialog-pO5amdj9.js`** _(6 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`download-Bh_vkCgZ.js`** _(7 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`ementas-BV15v3HA.js`** _(7 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`escritorio-Cl6tGFhQ.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`external-link-caavnAX0.js`** _(7 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`eye-DTa4_77d.js`** _(7 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`eye-off-BWv1vOKf.js`** _(7 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`file-text-D5YgGlaO.js`** _(7 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`filtrador-DXCOB_33.js`** _(45 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`gavel-Dwyyfr6c.js`** _(7 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`hash-CyyXtJxx.js`** _(7 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`historico-DDNTQq-I.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`history-B2Xyd_MK.js`** _(7 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`index-B-KQ3WUI.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`index-BdQq_4o_.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`index-CkZBBUpY.js`** _(232 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`index-CrvuR9uT.css`** _(2 linhas)_
Arquivo de estilos visuais — cores, tamanhos, fontes, espacamentos da interface.

**`index-DtqVP6cJ.js`** _(42 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`index-JNL3C0-P.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`index-hoeJRIQI.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`index-q_gTu9nj.js`** _(105 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`info-xwiNh27h.js`** _(7 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`input-BHYEJHxF.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`jurisprudencia-DjNf63tD.js`** _(80 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`key-H8121w75.js`** _(7 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`label-DDbKw7aq.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`legal-assistant-D8LNF6jM.js`** _(123 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`log-out-DcuqR1HY.js`** _(7 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`login-D--OVM-N.js`** _(7 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`mail-UeVcz8dw.js`** _(7 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`message-square-D63Lcg41.js`** _(7 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`not-found-BtLd1pRQ.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`painel-processos-Dx2B6hBz.js`** _(23 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`pdf-D-oSvAqu.js`** _(56 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`pencil-DFfVmNKN.js`** _(17 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`pje-BtNTwcaD.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`play-Dmy3Tr5S.js`** _(7 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`playground-CiFjVRYw.js`** _(425 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`plus-CHNfvhce.js`** _(7 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`prazos-BiyhxebU.js`** _(7 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`previdenciario-BgZf2Tbb.js`** _(20 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`refresh-cw-CUZ4KEwd.js`** _(7 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`robo-djen-cJK4ep0K.js`** _(5 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`rotate-ccw-BuKmPR_P.js`** _(7 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`save-C8RRHb15.js`** _(7 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`scale-GBhUYU-E.js`** _(7 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`search-jJ27H8hL.js`** _(7 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`select-DDIifz52.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`separator-Dfm4ZYD4.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`server-MMXj2nPg.js`** _(7 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`settings-D81hJRVO.js`** _(7 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`shield-DrACl4xC.js`** _(7 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`slider-CZPfl0zr.js`** _(47 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`status-CLTSdRTB.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`tabs-C8YWXfKh.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`tag-CzW8KDkR.js`** _(7 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`target-D1gUxVkr.js`** _(12 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`templates-juridicos-nosr4NEB.js`** _(651 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`terminal-jLiJtK1h.js`** _(7 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`textarea-CCtB2qGH.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`theme-toggle-Dbf3_SAN.js`** _(12 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`tiptap-editor-Df4ueogS.js`** _(217 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`token-generator-vOUVwjyA.js`** _(27 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`tramitacao-8LC-yeQF.js`** _(17 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`trash-2-Mk5MkyoA.js`** _(7 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`triangle-alert-v4TJhy5N.js`** _(7 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`upload-D1eWvUVm.js`** _(7 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`useMutation-BW5OEpvQ.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`user-JeTrnZj0.js`** _(7 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`user-check-CJpgpIJk.js`** _(7 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`users-BVC16TKt.js`** _(7 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`volume-x-B8490iQ3.js`** _(27 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`wifi-off-B1XPEx6z.js`** _(7 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`zap-DuTIlcWP.js`** _(12 linhas)_
Funcoes UTILITARIAS — ferramentas reutilizaveis de uso geral no projeto.

---

### 📁 `sk-mobile/.expo/web/cache/production/images/android-adaptive-foreground/android-adaptive-foreground-3b544823f512e77f9b3b3b4b73f1d24f0f05d2d6111352ce92d66c01f0741b9c-cover-transparent/`
> Pasta 'android-adaptive-foreground-3b544823f512e77f9b3b3b4b73f1d24f0f05d2d6111352ce92d66c01f0741b9c-cover-transparent' — agrupamento de arquivos relacionados.

**`icon_108.png`** _(1 linha)_
Arquivo de imagem.

**`icon_162.png`** _(1 linha)_
Arquivo de imagem.

**`icon_216.png`** _(1 linha)_
Arquivo de imagem.

**`icon_324.png`** _(1 linha)_
Arquivo de imagem.

**`icon_432.png`** _(1 linha)_
Arquivo de imagem.

---

### 📁 `sk-mobile/.expo/web/cache/production/images/android-standard-square/android-standard-square-3b544823f512e77f9b3b3b4b73f1d24f0f05d2d6111352ce92d66c01f0741b9c-cover-transparent/`
> Pasta 'android-standard-square-3b544823f512e77f9b3b3b4b73f1d24f0f05d2d6111352ce92d66c01f0741b9c-cover-transparent' — agrupamento de arquivos relacionados.

**`icon_144.png`** _(1 linha)_
Arquivo de imagem.

**`icon_192.png`** _(1 linha)_
Arquivo de imagem.

**`icon_48.png`** _(1 linha)_
Arquivo de imagem.

**`icon_72.png`** _(1 linha)_
Arquivo de imagem.

**`icon_96.png`** _(1 linha)_
Arquivo de imagem.

---

### 📁 `sk-mobile/.expo/web/cache/production/images/favicon/favicon-3b544823f512e77f9b3b3b4b73f1d24f0f05d2d6111352ce92d66c01f0741b9c-contain-transparent/`
> Pasta 'favicon-3b544823f512e77f9b3b3b4b73f1d24f0f05d2d6111352ce92d66c01f0741b9c-contain-transparent' — agrupamento de arquivos relacionados.

**`favicon-48.png`** _(1 linha)_
Arquivo de imagem.

---

### 📁 `sk-mobile/.expo/web/cache/production/images/splash-android/splash-android-3b544823f512e77f9b3b3b4b73f1d24f0f05d2d6111352ce92d66c01f0741b9c-contain/`
> Pasta 'splash-android-3b544823f512e77f9b3b3b4b73f1d24f0f05d2d6111352ce92d66c01f0741b9c-contain' — agrupamento de arquivos relacionados.

**`icon_200.png`** _(1 linha)_
Arquivo de imagem.

**`icon_300.png`** _(1 linha)_
Arquivo de imagem.

**`icon_400.png`** _(1 linha)_
Arquivo de imagem.

**`icon_600.png`** _(1 linha)_
Arquivo de imagem.

**`icon_800.png`** _(1 linha)_
Arquivo de imagem.

---

### 📁 `sk-mobile/android/app/src/main/java/com/anonymous/skmobile/`
> Pasta 'skmobile' — agrupamento de arquivos relacionados.

**`MainActivity.kt`** _(66 linhas)_
Arquivo KT — parte do projeto.

**`MainApplication.kt`** _(57 linhas)_
Arquivo KT — parte do projeto.

---

## CONTEXTO PARA IA (copie e cole para continuar o projeto)

> Use este bloco para explicar o projeto para qualquer IA ou desenvolvedor:

```
Projeto: HTML/CSS/JS
Tipo: Aplicacao Web Frontend (React)
Stack: React, TypeScript
Arquivos: 966 | Linhas: ~109.937
Rotas API: 60 endpoint(s) detectado(s)
Variaveis de ambiente necessarias: APP_URL, PORT, BASE_PATH, REPL_ID, ALLOWED_ORIGINS, JWT_SECRET, JWT_EXPIRES_IN, DATABASE_URL, GROQ_API_KEY, OPENAI_API_KEY, GEMINI_API_KEY, ANTHROPIC_API_KEY, XAI_API_KEY, OPENROUTER_API_KEY, PERPLEXITY_API_KEY, TELEGRAM_TOKEN, REPLIT_INTERNAL_APP_DOMAIN, REPLIT_DEV_DOMAIN, EXPO_PUBLIC_DOMAIN, EXPO_PUBLIC_REPL_ID

Estrutura principal:
  apk-builder/.replit-artifact/artifact.toml
  apk-builder/components.json
  apk-builder/dist/public/assets/XTermConnector-DkvdoLSY.js
  apk-builder/dist/public/assets/addon-fit-DX4qG4td.js
  apk-builder/dist/public/assets/addon-web-links-DIbG5aQx.js
  apk-builder/dist/public/assets/index-BayuCH0U.js
  apk-builder/dist/public/assets/index-DuH2u_vm.css
  apk-builder/dist/public/assets/xterm-B-qIQCd3.js
  apk-builder/dist/public/assistente-juridico-pwa.zip
  apk-builder/dist/public/favicon.svg
  apk-builder/dist/public/icon-192.png
  apk-builder/dist/public/icon-192.svg
  apk-builder/dist/public/icon-512.png
  apk-builder/dist/public/icon-512.svg
  apk-builder/dist/public/index.html
  apk-builder/dist/public/manifest.json
  apk-builder/dist/public/opengraph.jpg
  apk-builder/dist/public/sw.js
  apk-builder/index.html
  apk-builder/package.json
  apk-builder/public/favicon.svg
  apk-builder/public/icon-192.png
  apk-builder/public/icon-192.svg
  apk-builder/public/icon-512.png
  apk-builder/public/icon-512.svg
  apk-builder/public/manifest.json
  apk-builder/public/opengraph.jpg
  apk-builder/public/sw.js
  apk-builder/src/App.tsx
  apk-builder/src/components/ApkAnalyzer.tsx
  apk-builder/src/components/TerminalTab.tsx
  apk-builder/src/components/XTermConnector.tsx
  apk-builder/src/components/ui/accordion.tsx
  apk-builder/src/components/ui/alert-dialog.tsx
  apk-builder/src/components/ui/alert.tsx
  apk-builder/src/components/ui/aspect-ratio.tsx
  apk-builder/src/components/ui/avatar.tsx
  apk-builder/src/components/ui/badge.tsx
  apk-builder/src/components/ui/breadcrumb.tsx
  apk-builder/src/components/ui/button-group.tsx
  apk-builder/src/components/ui/button.tsx
  apk-builder/src/components/ui/calendar.tsx
  apk-builder/src/components/ui/card.tsx
  apk-builder/src/components/ui/carousel.tsx
  apk-builder/src/components/ui/chart.tsx
  apk-builder/src/components/ui/checkbox.tsx
  apk-builder/src/components/ui/collapsible.tsx
  apk-builder/src/components/ui/command.tsx
  apk-builder/src/components/ui/context-menu.tsx
  apk-builder/src/components/ui/dialog.tsx
  apk-builder/src/components/ui/drawer.tsx
  apk-builder/src/components/ui/dropdown-menu.tsx
  apk-builder/src/components/ui/empty.tsx
  apk-builder/src/components/ui/field.tsx
  apk-builder/src/components/ui/form.tsx
  apk-builder/src/components/ui/hover-card.tsx
  apk-builder/src/components/ui/input-group.tsx
  apk-builder/src/components/ui/input-otp.tsx
  apk-builder/src/components/ui/input.tsx
  apk-builder/src/components/ui/item.tsx
  apk-builder/src/components/ui/kbd.tsx
  apk-builder/src/components/ui/label.tsx
  apk-builder/src/components/ui/menubar.tsx
  apk-builder/src/components/ui/navigation-menu.tsx
  apk-builder/src/components/ui/pagination.tsx
  apk-builder/src/components/ui/popover.tsx
  apk-builder/src/components/ui/progress.tsx
  apk-builder/src/components/ui/radio-group.tsx
  apk-builder/src/components/ui/resizable.tsx
  apk-builder/src/components/ui/scroll-area.tsx
  apk-builder/src/components/ui/select.tsx
  apk-builder/src/components/ui/separator.tsx
  apk-builder/src/components/ui/sheet.tsx
  apk-builder/src/components/ui/sidebar.tsx
  apk-builder/src/components/ui/skeleton.tsx
  apk-builder/src/components/ui/slider.tsx
  apk-builder/src/components/ui/sonner.tsx
  apk-builder/src/components/ui/spinner.tsx
  apk-builder/src/components/ui/switch.tsx
  apk-builder/src/components/ui/table.tsx
  apk-builder/src/components/ui/tabs.tsx
  apk-builder/src/components/ui/textarea.tsx
  apk-builder/src/components/ui/toast.tsx
  apk-builder/src/components/ui/toaster.tsx
  apk-builder/src/components/ui/toggle-group.tsx
  apk-builder/src/components/ui/toggle.tsx
  apk-builder/src/components/ui/tooltip.tsx
  apk-builder/src/hooks/use-mobile.tsx
  apk-builder/src/hooks/use-toast.ts
  apk-builder/src/index.css
  apk-builder/src/lib/android.ts
  apk-builder/src/lib/archive.ts
  apk-builder/src/lib/github.ts
  apk-builder/src/lib/storage.ts
  apk-builder/src/lib/utils.ts
  apk-builder/src/main.tsx
  apk-builder/src/pages/not-found.tsx
  apk-builder/tsconfig.json
  apk-builder/vite.config.ts
  assistente-juridico/android/.gradle/8.14.3/checksums/checksums.lock
  assistente-juridico/android/.gradle/8.14.3/checksums/md5-checksums.bin
  assistente-juridico/android/.gradle/8.14.3/checksums/sha1-checksums.bin
  assistente-juridico/android/.gradle/8.14.3/executionHistory/executionHistory.bin
  assistente-juridico/android/.gradle/8.14.3/executionHistory/executionHistory.lock
  assistente-juridico/android/.gradle/8.14.3/fileChanges/last-build.bin
  assistente-juridico/android/.gradle/8.14.3/fileHashes/fileHashes.bin
  assistente-juridico/android/.gradle/8.14.3/fileHashes/fileHashes.lock
  assistente-juridico/android/.gradle/8.14.3/fileHashes/resourceHashesCache.bin
  assistente-juridico/android/.gradle/8.14.3/gc.properties
  assistente-juridico/android/.gradle/buildOutputCleanup/buildOutputCleanup.lock
  assistente-juridico/android/.gradle/buildOutputCleanup/cache.properties
  assistente-juridico/android/.gradle/buildOutputCleanup/outputFiles.bin
  assistente-juridico/android/.gradle/vcs-1/gc.properties
  assistente-juridico/android/app/src/main/assets/capacitor.config.json
  assistente-juridico/android/app/src/main/assets/capacitor.plugins.json
  assistente-juridico/android/app/src/main/assets/public/SK-Juridico-IA.apk
  assistente-juridico/android/app/src/main/assets/public/assets/admin-wZRLZyDy.js
  assistente-juridico/android/app/src/main/assets/public/assets/arrow-left-DYElIYXR.js
  assistente-juridico/android/app/src/main/assets/public/assets/assinatura-BHt3Qvse.js
  assistente-juridico/android/app/src/main/assets/public/assets/auditoria-financeira-C-CiXcAZ.js
  assistente-juridico/android/app/src/main/assets/public/assets/badge-BCXvIIul.js
  assistente-juridico/android/app/src/main/assets/public/assets/bell-B5W5rjOr.js
  assistente-juridico/android/app/src/main/assets/public/assets/book-open-CctBA1uj.js
  assistente-juridico/android/app/src/main/assets/public/assets/bot-B-04Xe7b.js
  assistente-juridico/android/app/src/main/assets/public/assets/briefcase-jFpqll2q.js
  assistente-juridico/android/app/src/main/assets/public/assets/building-2-ywDJkoHl.js
  assistente-juridico/android/app/src/main/assets/public/assets/button-D5ZhSwEd.js
  assistente-juridico/android/app/src/main/assets/public/assets/calendar-B664tU9C.js
  assistente-juridico/android/app/src/main/assets/public/assets/card-BtrX4egs.js
  assistente-juridico/android/app/src/main/assets/public/assets/check-CwxI4-xR.js
  assistente-juridico/android/app/src/main/assets/public/assets/chevron-down-uth5WLjM.js
  assistente-juridico/android/app/src/main/assets/public/assets/chevron-left-BRbXarL_.js
  assistente-juridico/android/app/src/main/assets/public/assets/chevron-right-CedePU1E.js
  assistente-juridico/android/app/src/main/assets/public/assets/chevron-up-C9iGwLbl.js
  assistente-juridico/android/app/src/main/assets/public/assets/circle-CG12gPnc.js
  assistente-juridico/android/app/src/main/assets/public/assets/circle-alert-DPHqLNmk.js
  assistente-juridico/android/app/src/main/assets/public/assets/circle-x-CwgzW83o.js
  assistente-juridico/android/app/src/main/assets/public/assets/clock-D9M-tegz.js
  assistente-juridico/android/app/src/main/assets/public/assets/codigo-CFUnhIfo.js
  assistente-juridico/android/app/src/main/assets/public/assets/colaborativo-COD6aFte.js
  assistente-juridico/android/app/src/main/assets/public/assets/comparador-juridico-DYsbk112.js
  assistente-juridico/android/app/src/main/assets/public/assets/comunicacoes-cnj-CJy6IPR8.js
  assistente-juridico/android/app/src/main/assets/public/assets/configuracoes-BuhDceYz.js
  assistente-juridico/android/app/src/main/assets/public/assets/consulta-corporativo-BSKcbntC.js
  assistente-juridico/android/app/src/main/assets/public/assets/consulta-pdpj-BtJMr5YB.js
  assistente-juridico/android/app/src/main/assets/public/assets/consulta-processual-CS_HcDnj.js
  assistente-juridico/android/app/src/main/assets/public/assets/copy-C0ymX2fa.js
  assistente-juridico/android/app/src/main/assets/public/assets/cpu-z3we3BDw.js
  assistente-juridico/android/app/src/main/assets/public/assets/database-CYrcrLbK.js
  assistente-juridico/android/app/src/main/assets/public/assets/dialog-pO5amdj9.js
  assistente-juridico/android/app/src/main/assets/public/assets/download-Bh_vkCgZ.js
  assistente-juridico/android/app/src/main/assets/public/assets/ementas-BV15v3HA.js
  assistente-juridico/android/app/src/main/assets/public/assets/escritorio-Cl6tGFhQ.js
  assistente-juridico/android/app/src/main/assets/public/assets/external-link-caavnAX0.js
  assistente-juridico/android/app/src/main/assets/public/assets/eye-DTa4_77d.js
  assistente-juridico/android/app/src/main/assets/public/assets/eye-off-BWv1vOKf.js
  assistente-juridico/android/app/src/main/assets/public/assets/file-text-D5YgGlaO.js
  assistente-juridico/android/app/src/main/assets/public/assets/filtrador-DXCOB_33.js
  assistente-juridico/android/app/src/main/assets/public/assets/gavel-Dwyyfr6c.js
  assistente-juridico/android/app/src/main/assets/public/assets/hash-CyyXtJxx.js
  assistente-juridico/android/app/src/main/assets/public/assets/historico-DDNTQq-I.js
  assistente-juridico/android/app/src/main/assets/public/assets/history-B2Xyd_MK.js
  assistente-juridico/android/app/src/main/assets/public/assets/index-B-KQ3WUI.js
  assistente-juridico/android/app/src/main/assets/public/assets/index-BdQq_4o_.js
  assistente-juridico/android/app/src/main/assets/public/assets/index-CkZBBUpY.js
  assistente-juridico/android/app/src/main/assets/public/assets/index-CrvuR9uT.css
  assistente-juridico/android/app/src/main/assets/public/assets/index-DtqVP6cJ.js
  assistente-juridico/android/app/src/main/assets/public/assets/index-JNL3C0-P.js
  assistente-juridico/android/app/src/main/assets/public/assets/index-hoeJRIQI.js
  assistente-juridico/android/app/src/main/assets/public/assets/index-q_gTu9nj.js
  assistente-juridico/android/app/src/main/assets/public/assets/info-xwiNh27h.js
  assistente-juridico/android/app/src/main/assets/public/assets/input-BHYEJHxF.js
  assistente-juridico/android/app/src/main/assets/public/assets/jurisprudencia-DjNf63tD.js
  assistente-juridico/android/app/src/main/assets/public/assets/key-H8121w75.js
  assistente-juridico/android/app/src/main/assets/public/assets/label-DDbKw7aq.js
  assistente-juridico/android/app/src/main/assets/public/assets/legal-assistant-D8LNF6jM.js
  assistente-juridico/android/app/src/main/assets/public/assets/log-out-DcuqR1HY.js
  assistente-juridico/android/app/src/main/assets/public/assets/login-D--OVM-N.js
  assistente-juridico/android/app/src/main/assets/public/assets/mail-UeVcz8dw.js
  assistente-juridico/android/app/src/main/assets/public/assets/message-square-D63Lcg41.js
  assistente-juridico/android/app/src/main/assets/public/assets/not-found-BtLd1pRQ.js
  assistente-juridico/android/app/src/main/assets/public/assets/painel-processos-Dx2B6hBz.js
  assistente-juridico/android/app/src/main/assets/public/assets/pdf-D-oSvAqu.js
  assistente-juridico/android/app/src/main/assets/public/assets/pencil-DFfVmNKN.js
  assistente-juridico/android/app/src/main/assets/public/assets/pje-BtNTwcaD.js
  assistente-juridico/android/app/src/main/assets/public/assets/play-Dmy3Tr5S.js
  assistente-juridico/android/app/src/main/assets/public/assets/playground-CiFjVRYw.js
  assistente-juridico/android/app/src/main/assets/public/assets/plus-CHNfvhce.js
  assistente-juridico/android/app/src/main/assets/public/assets/prazos-BiyhxebU.js
  assistente-juridico/android/app/src/main/assets/public/assets/previdenciario-BgZf2Tbb.js
  assistente-juridico/android/app/src/main/assets/public/assets/refresh-cw-CUZ4KEwd.js
  assistente-juridico/android/app/src/main/assets/public/assets/robo-djen-cJK4ep0K.js
  assistente-juridico/android/app/src/main/assets/public/assets/rotate-ccw-BuKmPR_P.js
  assistente-juridico/android/app/src/main/assets/public/assets/save-C8RRHb15.js
  assistente-juridico/android/app/src/main/assets/public/assets/scale-GBhUYU-E.js
  assistente-juridico/android/app/src/main/assets/public/assets/search-jJ27H8hL.js
  assistente-juridico/android/app/src/main/assets/public/assets/select-DDIifz52.js
  assistente-juridico/android/app/src/main/assets/public/assets/separator-Dfm4ZYD4.js
  assistente-juridico/android/app/src/main/assets/public/assets/server-MMXj2nPg.js
  assistente-juridico/android/app/src/main/assets/public/assets/settings-D81hJRVO.js
  assistente-juridico/android/app/src/main/assets/public/assets/shield-DrACl4xC.js
  assistente-juridico/android/app/src/main/assets/public/assets/slider-CZPfl0zr.js
  assistente-juridico/android/app/src/main/assets/public/assets/status-CLTSdRTB.js
  assistente-juridico/android/app/src/main/assets/public/assets/tabs-C8YWXfKh.js
  assistente-juridico/android/app/src/main/assets/public/assets/tag-CzW8KDkR.js
  assistente-juridico/android/app/src/main/assets/public/assets/target-D1gUxVkr.js
  assistente-juridico/android/app/src/main/assets/public/assets/templates-juridicos-nosr4NEB.js
  assistente-juridico/android/app/src/main/assets/public/assets/terminal-jLiJtK1h.js
  assistente-juridico/android/app/src/main/assets/public/assets/textarea-CCtB2qGH.js
  assistente-juridico/android/app/src/main/assets/public/assets/theme-toggle-Dbf3_SAN.js
  assistente-juridico/android/app/src/main/assets/public/assets/tiptap-editor-Df4ueogS.js
  assistente-juridico/android/app/src/main/assets/public/assets/token-generator-vOUVwjyA.js
  assistente-juridico/android/app/src/main/assets/public/assets/tramitacao-8LC-yeQF.js
  assistente-juridico/android/app/src/main/assets/public/assets/trash-2-Mk5MkyoA.js
  assistente-juridico/android/app/src/main/assets/public/assets/triangle-alert-v4TJhy5N.js
  assistente-juridico/android/app/src/main/assets/public/assets/upload-D1eWvUVm.js
  assistente-juridico/android/app/src/main/assets/public/assets/useMutation-BW5OEpvQ.js
  assistente-juridico/android/app/src/main/assets/public/assets/user-JeTrnZj0.js
  assistente-juridico/android/app/src/main/assets/public/assets/user-check-CJpgpIJk.js
  assistente-juridico/android/app/src/main/assets/public/assets/users-BVC16TKt.js
  assistente-juridico/android/app/src/main/assets/public/assets/volume-x-B8490iQ3.js
  assistente-juridico/android/app/src/main/assets/public/assets/wifi-off-B1XPEx6z.js
  assistente-juridico/android/app/src/main/assets/public/assets/zap-DuTIlcWP.js
  assistente-juridico/android/app/src/main/assets/public/cordova.js
  assistente-juridico/android/app/src/main/assets/public/cordova_plugins.js
  assistente-juridico/android/app/src/main/assets/public/favicon.svg
  assistente-juridico/android/app/src/main/assets/public/icon-192.png
  assistente-juridico/android/app/src/main/assets/public/icon-384.png
  assistente-juridico/android/app/src/main/assets/public/icon-512.png
  assistente-juridico/android/app/src/main/assets/public/icon-96.png
  assistente-juridico/android/app/src/main/assets/public/index.html
  assistente-juridico/android/app/src/main/assets/public/manifest.json
  assistente-juridico/android/app/src/main/assets/public/opengraph.jpg
  assistente-juridico/android/app/src/main/assets/public/robots.txt
  assistente-juridico/android/app/src/main/assets/public/sw.js
  assistente-juridico/android/app/src/main/res/xml/config.xml
  assistente-juridico/android/capacitor-cordova-android-plugins/build.gradle
  assistente-juridico/android/capacitor-cordova-android-plugins/cordova.variables.gradle
  assistente-juridico/android/capacitor-cordova-android-plugins/src/main/AndroidManifest.xml
  assistente-juridico/android/capacitor-cordova-android-plugins/src/main/java/.gitkeep
  assistente-juridico/android/capacitor-cordova-android-plugins/src/main/res/.gitkeep
  assistente-juridico/android/local.properties
  assistente-juridico/dist/assets/admin-DdVWhbJZ.js
  assistente-juridico/dist/assets/arrow-left-nBCyQW32.js
  assistente-juridico/dist/assets/assinatura-DhMNHOKB.js
  assistente-juridico/dist/assets/badge-CeQ9YgHg.js
  assistente-juridico/dist/assets/bell-S8SoMvhJ.js
  assistente-juridico/dist/assets/book-open-jGqVCAaa.js
  assistente-juridico/dist/assets/bot-BPZdrzKs.js
  assistente-juridico/dist/assets/briefcase-JIjjIAIQ.js
  assistente-juridico/dist/assets/building-2-DuXwQ01A.js
  assistente-juridico/dist/assets/button-DogYNL8m.js
  assistente-juridico/dist/assets/calendar-C8eS9BJ3.js
  assistente-juridico/dist/assets/card-CAMPMs4I.js
  assistente-juridico/dist/assets/check-Cw4MhVxd.js
  assistente-juridico/dist/assets/chevron-down-CSLxLrLQ.js
  assistente-juridico/dist/assets/chevron-left-D8dWNoIe.js
  assistente-juridico/dist/assets/chevron-right-QUxraXO5.js
  assistente-juridico/dist/assets/chevron-up-B-NrD1Yf.js
  assistente-juridico/dist/assets/circle-CpSIygtO.js
  assistente-juridico/dist/assets/circle-alert-CODgC0Wt.js
  assistente-juridico/dist/assets/circle-check-BvyNknoB.js
  assistente-juridico/dist/assets/circle-x-BI8lMh8t.js
  assistente-juridico/dist/assets/clock-Cp3l2mis.js
  assistente-juridico/dist/assets/codigo-CBvzBZYN.js
  assistente-juridico/dist/assets/colaborativo-Bmjhl7Bs.js
  assistente-juridico/dist/assets/comparador-juridico-e11bTEP1.js
  assistente-juridico/dist/assets/comunicacoes-cnj-DF3LmGtR.js
  assistente-juridico/dist/assets/configuracoes-DyhSBsZW.js
  assistente-juridico/dist/assets/consulta-corporativo-AH19UW8F.js
  assistente-juridico/dist/assets/consulta-pdpj-CmwGfWNe.js
  assistente-juridico/dist/assets/consulta-processual-DT9PR3AD.js
  assistente-juridico/dist/assets/copy-BJbuHhiB.js
  assistente-juridico/dist/assets/cpu-H9bqy-ol.js
  assistente-juridico/dist/assets/database-DPXDRvNh.js
  assistente-juridico/dist/assets/dialog-BW4Lb6A6.js
  assistente-juridico/dist/assets/download-CYbqGIYu.js
  assistente-juridico/dist/assets/ementas-GuvS-wAN.js
  assistente-juridico/dist/assets/escritorio-D5Xc-ipL.js
  assistente-juridico/dist/assets/external-link-CEf6uMDg.js
  assistente-juridico/dist/assets/eye-NEq-3FD4.js
  assistente-juridico/dist/assets/eye-off-BkyV4iqA.js
  assistente-juridico/dist/assets/file-text-CVJYXn7I.js
  assistente-juridico/dist/assets/filtrador-Uh5o5CGF.js
  assistente-juridico/dist/assets/gavel-7xOSQuEL.js
  assistente-juridico/dist/assets/globe-DqXCJqaQ.js
  assistente-juridico/dist/assets/hash-DXrFETIG.js
  assistente-juridico/dist/assets/historico-BHc_45HR.js
  assistente-juridico/dist/assets/history-Dm5s-98n.js
  assistente-juridico/dist/assets/index-B-_-zVh9.js
  assistente-juridico/dist/assets/index-BdQq_4o_.js
  assistente-juridico/dist/assets/index-Cajry1w2.js
  assistente-juridico/dist/assets/index-DGVWKFBB.js
  assistente-juridico/dist/assets/index-Dha_x3eW.js
  assistente-juridico/dist/assets/index-Do0OOi2v.css
  assistente-juridico/dist/assets/index-Dt5FInq3.js
  assistente-juridico/dist/assets/index-ZJT4jjP1.js
  assistente-juridico/dist/assets/info-Bv65dD_K.js
  assistente-juridico/dist/assets/input-BsVrziBy.js
  assistente-juridico/dist/assets/jurisprudencia-OuGxXOY4.js
  assistente-juridico/dist/assets/key-Ba8qnwem.js
  assistente-juridico/dist/assets/label-Cc5cm9uG.js
  assistente-juridico/dist/assets/legal-assistant-v7qssgXW.js
  assistente-juridico/dist/assets/log-out-C1v4nIPP.js
  assistente-juridico/dist/assets/login-7hMOiJ2J.js
  assistente-juridico/dist/assets/mail-DIZQZj_s.js
  assistente-juridico/dist/assets/message-square-D_Z2gJKw.js
  assistente-juridico/dist/assets/not-found-DSZWET4-.js
  assistente-juridico/dist/assets/painel-processos-B7i2NMof.js
  assistente-juridico/dist/assets/pdf-B75MOh95.js
  assistente-juridico/dist/assets/pencil-Q_CBYcqn.js
  assistente-juridico/dist/assets/pje-9CSE9fDi.js
  assistente-juridico/dist/assets/play-DfmtkRyB.js
  assistente-juridico/dist/assets/playground-DD29hz3O.js
  assistente-juridico/dist/assets/plus-DfNIQMpt.js
  assistente-juridico/dist/assets/prazos-DF6K-tvm.js
  assistente-juridico/dist/assets/previdenciario-DkaB0ujZ.js
  assistente-juridico/dist/assets/refresh-cw-D5__vk8G.js
  assistente-juridico/dist/assets/robo-djen-D3WPdr0u.js
  assistente-juridico/dist/assets/rotate-ccw-D28OuoVq.js
  assistente-juridico/dist/assets/save-BnF37M3_.js
  assistente-juridico/dist/assets/scale-i6eM2OQ9.js
  assistente-juridico/dist/assets/search-B1p4_U_k.js
  assistente-juridico/dist/assets/select-DutfNDZp.js
  assistente-juridico/dist/assets/separator-DQXp5lNG.js
  assistente-juridico/dist/assets/server-DNeVClqP.js
  assistente-juridico/dist/assets/settings-Cudh-Mnh.js
  assistente-juridico/dist/assets/shield-CeeBT9p1.js
  assistente-juridico/dist/assets/slider-D0R0PB6j.js
  assistente-juridico/dist/assets/status-B5oxDYuU.js
  assistente-juridico/dist/assets/tabs-DnoBjg6K.js
  assistente-juridico/dist/assets/tag-B3no2Wh0.js
  assistente-juridico/dist/assets/target-BCM4Kr-t.js
  assistente-juridico/dist/assets/templates-juridicos-1Iq21zIV.js
  assistente-juridico/dist/assets/terminal-BajxkcBh.js
  assistente-juridico/dist/assets/textarea-CDo_t3Pz.js
  assistente-juridico/dist/assets/theme-toggle-DD5PSROF.js
  assistente-juridico/dist/assets/tiptap-editor-DxlsD-7E.js
  assistente-juridico/dist/assets/token-generator-OcTrrzh7.js
  assistente-juridico/dist/assets/tramitacao-BxlsSwUG.js
  assistente-juridico/dist/assets/trash-2-DDvNxfXN.js
  assistente-juridico/dist/assets/triangle-alert-DSonC7Kt.js
  assistente-juridico/dist/assets/upload-Bl3wdvk6.js
  assistente-juridico/dist/assets/useMutation-DjoeqaNn.js
  assistente-juridico/dist/assets/user-7yy-BCdS.js
  assistente-juridico/dist/assets/user-check-vp_bBrF6.js
  assistente-juridico/dist/assets/users-DONy9nTq.js
  assistente-juridico/dist/assets/volume-x-DcwW5KKL.js
  assistente-juridico/dist/assets/wifi-B6Kj2hWi.js
  assistente-juridico/dist/assets/zap-uo4Z6IN6.js
  assistente-juridico/dist/cordova.js
  assistente-juridico/dist/cordova_plugins.js
  assistente-juridico/dist/favicon.svg
  assistente-juridico/dist/icon-192.png
  assistente-juridico/dist/icon-384.png
  assistente-juridico/dist/icon-512.png
  assistente-juridico/dist/icon-96.png
  assistente-juridico/dist/index.html
  assistente-juridico/dist/manifest.json
  assistente-juridico/dist/opengraph.jpg
  assistente-juridico/dist/public/SK-Juridico-IA-v1.8.apk
  assistente-juridico/dist/public/SK-Juridico-IA.apk
  assistente-juridico/dist/public/assets/admin-CBkE_xRa.js
  assistente-juridico/dist/public/assets/arrow-left-De2M_wPP.js
  assistente-juridico/dist/public/assets/assinatura-BxGVlQr8.js
  assistente-juridico/dist/public/assets/badge-DvsEBxZE.js
  assistente-juridico/dist/public/assets/bell-BAx4uqwM.js
  assistente-juridico/dist/public/assets/book-open-C60h3AJh.js
  assistente-juridico/dist/public/assets/bot-CQEA4oRY.js
  assistente-juridico/dist/public/assets/building-2-BXpbgOaa.js
  assistente-juridico/dist/public/assets/button-BUGwJ1r4.js
  assistente-juridico/dist/public/assets/calendar-Bn-2Hr63.js
  assistente-juridico/dist/public/assets/card-mbB_popU.js
  assistente-juridico/dist/public/assets/check-efW8jyn0.js
  assistente-juridico/dist/public/assets/chevron-down-r3_9_CMA.js
  assistente-juridico/dist/public/assets/chevron-left-BLKLetW2.js
  assistente-juridico/dist/public/assets/chevron-right-BzsbPMa4.js
  assistente-juridico/dist/public/assets/chevron-up-KuwEdWNQ.js
  assistente-juridico/dist/public/assets/circle-DjYp1w7I.js
  assistente-juridico/dist/public/assets/circle-alert-eSv2vETe.js
  assistente-juridico/dist/public/assets/circle-check-B6Hbs4xE.js
  assistente-juridico/dist/public/assets/circle-x-gjVK4Jgn.js
  assistente-juridico/dist/public/assets/clock-C4R428W7.js
  assistente-juridico/dist/public/assets/codigo-DICocSqs.js
  assistente-juridico/dist/public/assets/colaborativo-CCSq-6n3.js
  assistente-juridico/dist/public/assets/comparador-juridico-349a-1z6.js
  assistente-juridico/dist/public/assets/comunicacoes-cnj-Bz91U-FP.js
  assistente-juridico/dist/public/assets/configuracoes-Ct8H_2FW.js
  assistente-juridico/dist/public/assets/consulta-corporativo-DM1UUrc5.js
  assistente-juridico/dist/public/assets/consulta-pdpj-3DTOMKnM.js
  assistente-juridico/dist/public/assets/consulta-processual-Cw2Gu7NA.js
  assistente-juridico/dist/public/assets/copy-BFLCPv5x.js
  assistente-juridico/dist/public/assets/cpu-C024Qcuy.js
  assistente-juridico/dist/public/assets/database-DLAbLVck.js
  assistente-juridico/dist/public/assets/dialog-BAg_0Wok.js
  assistente-juridico/dist/public/assets/download-DuwWgM3Q.js
  assistente-juridico/dist/public/assets/ementas-CJZty0Wh.js
  assistente-juridico/dist/public/assets/escritorio-BLm-INPe.js
  assistente-juridico/dist/public/assets/external-link-BxUuqUaE.js
  assistente-juridico/dist/public/assets/eye-GP31qHS-.js
  assistente-juridico/dist/public/assets/eye-off-CnZx4Rv_.js
  assistente-juridico/dist/public/assets/file-text-Bv5C0iRI.js
  assistente-juridico/dist/public/assets/filtrador-ChgRMOq6.js
  assistente-juridico/dist/public/assets/gavel-BJpPYw1K.js
  assistente-juridico/dist/public/assets/historico-oQEcg4nM.js
  assistente-juridico/dist/public/assets/history-2mjGnPtq.js
  assistente-juridico/dist/public/assets/index-39mgIYgx.js
  assistente-juridico/dist/public/assets/index-AUXLjOsf.js
  assistente-juridico/dist/public/assets/index-BVE5xndR.js
  assistente-juridico/dist/public/assets/index-BdQq_4o_.js
  assistente-juridico/dist/public/assets/index-DOQDzLwe.js
  assistente-juridico/dist/public/assets/index-DOpuvYws.css
  assistente-juridico/dist/public/assets/index-Dju8vJgD.js
  assistente-juridico/dist/public/assets/index-MfVsal_x.js
  assistente-juridico/dist/public/assets/info-CTTXh9QD.js
  assistente-juridico/dist/public/assets/input-LSRw2cwy.js
  assistente-juridico/dist/public/assets/jurisprudencia-B2y-dTXc.js
  assistente-juridico/dist/public/assets/key-BBkVXwEW.js
  assistente-juridico/dist/public/assets/label-OX8Mn1-0.js
  assistente-juridico/dist/public/assets/legal-assistant-A7mZ5Kt6.js
  assistente-juridico/dist/public/assets/log-out-Bw9EOYRA.js
  assistente-juridico/dist/public/assets/login-Dzsw5OEx.js
  assistente-juridico/dist/public/assets/mail-BNiJ5jWe.js
  assistente-juridico/dist/public/assets/message-square-0jM2-GKg.js
  assistente-juridico/dist/public/assets/not-found-Dpb2K0qk.js
  assistente-juridico/dist/public/assets/painel-processos-CcOi2au5.js
  assistente-juridico/dist/public/assets/pdf-B75MOh95.js
  assistente-juridico/dist/public/assets/pencil-DBnBVZSc.js
  assistente-juridico/dist/public/assets/pje-mlPLPa45.js
  assistente-juridico/dist/public/assets/play-Dk83ynRF.js
  assistente-juridico/dist/public/assets/playground-CZrotIxo.js
  assistente-juridico/dist/public/assets/plus-Du7Lo3bz.js
  assistente-juridico/dist/public/assets/prazos-Pg0PZw65.js
  assistente-juridico/dist/public/assets/refresh-cw-GPND3eQm.js
  assistente-juridico/dist/public/assets/robo-djen-Ix2S-0G6.js
  assistente-juridico/dist/public/assets/rotate-ccw-Cg5i5ug3.js
  assistente-juridico/dist/public/assets/save-DOpTQH4r.js
  assistente-juridico/dist/public/assets/scale-BfcSY8rh.js
  assistente-juridico/dist/public/assets/search-rmZIdwX6.js
  assistente-juridico/dist/public/assets/select-Bnqk4twF.js
  assistente-juridico/dist/public/assets/separator-D_rvx2CS.js
  assistente-juridico/dist/public/assets/server-DbDCGMHt.js
  assistente-juridico/dist/public/assets/settings-BCCdn6tP.js
  assistente-juridico/dist/public/assets/shield-BaXcWJi9.js
  assistente-juridico/dist/public/assets/slider-CiGH8XhB.js
  assistente-juridico/dist/public/assets/status-CQbd-8UQ.js
  assistente-juridico/dist/public/assets/tabs-BgH_zz7Z.js
  assistente-juridico/dist/public/assets/tag-BHLeQaPL.js
  assistente-juridico/dist/public/assets/target-BD3QZD5M.js
  assistente-juridico/dist/public/assets/templates-juridicos-1ZiNvz08.js
  assistente-juridico/dist/public/assets/terminal-DjCaBnXe.js
  assistente-juridico/dist/public/assets/textarea-CW5o07-G.js
  assistente-juridico/dist/public/assets/theme-toggle-DxQ7IR8r.js
  assistente-juridico/dist/public/assets/tiptap-editor-CMlHrtsu.js
  assistente-juridico/dist/public/assets/token-generator-BGC3zoEJ.js
  assistente-juridico/dist/public/assets/tramitacao-DsUHMM8Q.js
  assistente-juridico/dist/public/assets/trash-2-DEBfAqIY.js
  assistente-juridico/dist/public/assets/triangle-alert-B4YV2-Gk.js
  assistente-juridico/dist/public/assets/upload-Cj7-ngfC.js
  assistente-juridico/dist/public/assets/useMutation-BJ86liox.js
  assistente-juridico/dist/public/assets/user-B9hczYUr.js
  assistente-juridico/dist/public/assets/user-check-DrvS6C4f.js
  assistente-juridico/dist/public/assets/users-DB2QB59g.js
  assistente-juridico/dist/public/assets/volume-x-CTBNzjlm.js
  assistente-juridico/dist/public/assets/wifi-off-CbHSy9GE.js
  assistente-juridico/dist/public/assets/zap-B2kCwK0T.js
  assistente-juridico/dist/public/favicon.svg
  assistente-juridico/dist/public/icon-192.png
  assistente-juridico/dist/public/icon-384.png
  assistente-juridico/dist/public/icon-512.png
  assistente-juridico/dist/public/icon-96.png
  assistente-juridico/dist/public/index.html
  assistente-juridico/dist/public/manifest.json
  assistente-juridico/dist/public/opengraph.jpg
  assistente-juridico/dist/public/robots.txt
  assistente-juridico/dist/public/setup-preview.html
  assistente-juridico/dist/public/sw.js
  assistente-juridico/dist/robots.txt
  assistente-juridico/dist/sw.js
  juridico/.replit-artifact/artifact.toml
  juridico/components.json
  juridico/dist/public/assets/admin-CSYibXzg.js
  juridico/dist/public/assets/arrow-left-DBwtgAcy.js
  juridico/dist/public/assets/assinatura-CpoFU8iN.js
  juridico/dist/public/assets/audio-lines-DsBMIcUK.js
  juridico/dist/public/assets/auditoria-financeira-BTiZ_MnQ.js
  juridico/dist/public/assets/badge-CD7rZS7n.js
  juridico/dist/public/assets/bell-Cht0EACw.js
  juridico/dist/public/assets/book-open-BKWsciMp.js
  juridico/dist/public/assets/bot-CpPmyCuP.js
  juridico/dist/public/assets/briefcase-B5MNLBsd.js
  juridico/dist/public/assets/building-2-CEkB_bNa.js
  juridico/dist/public/assets/button-DmWEFtXm.js
  juridico/dist/public/assets/calendar-wAE2F37_.js
  juridico/dist/public/assets/card-BipkLjeB.js
  juridico/dist/public/assets/check-BnLyF3Wu.js
  juridico/dist/public/assets/chevron-down-C8pb4oN1.js
  juridico/dist/public/assets/chevron-left-CCCXiGGa.js
  juridico/dist/public/assets/chevron-right-D1ryeHHM.js
  juridico/dist/public/assets/chevron-up-Cge-G70_.js
  juridico/dist/public/assets/circle-BASCHiMY.js
  juridico/dist/public/assets/circle-alert-nMBd91WP.js
  juridico/dist/public/assets/circle-check-CM4Qdbnm.js
  juridico/dist/public/assets/circle-stop-C2ikIssX.js
  juridico/dist/public/assets/circle-x-qu7znTBo.js
  juridico/dist/public/assets/clock-BbEb8j2V.js
  juridico/dist/public/assets/codigo-CcBp48WS.js
  juridico/dist/public/assets/colaborativo-D6VQuPIO.js
  juridico/dist/public/assets/comparador-juridico-Cliqnr15.js
  juridico/dist/public/assets/comunicacoes-cnj-BeEOY83h.js
  juridico/dist/public/assets/configuracoes-BSFwYNAK.js
  juridico/dist/public/assets/consulta-corporativo-BWNqd6Yg.js
  juridico/dist/public/assets/consulta-pdpj-CF1e66rQ.js
  juridico/dist/public/assets/consulta-processual-DDmG4iSv.js
  juridico/dist/public/assets/copy-C7yzOVrI.js
  juridico/dist/public/assets/cpu-BYm_2wvI.js
  juridico/dist/public/assets/database-Dllzk6br.js
  juridico/dist/public/assets/dialog-C_UTeQ-Z.js
  juridico/dist/public/assets/download-DnUulWCg.js
  juridico/dist/public/assets/ementas-AisZ7hh-.js
  juridico/dist/public/assets/escritorio-DlPQALZe.js
  juridico/dist/public/assets/external-link-BgiAxW7g.js
  juridico/dist/public/assets/eye-off-DNQQfmQu.js
  juridico/dist/public/assets/eye-sSfRAZ3B.js
  juridico/dist/public/assets/file-text-DeLlVhKq.js
  juridico/dist/public/assets/fileExtract-DHdlQI-A.js
  juridico/dist/public/assets/filtrador-cyiDAYMn.js
  juridico/dist/public/assets/folder-open-Hodf7wN5.js
  juridico/dist/public/assets/gavel-B06xpq47.js
  juridico/dist/public/assets/globe-DuhDY7M0.js
  juridico/dist/public/assets/guia-C7Wlu1qL.js
  juridico/dist/public/assets/hash-Bw4xy2Sx.js
  juridico/dist/public/assets/historico-CLCC7I0D.js
  juridico/dist/public/assets/history-ByeCVPNp.js
  juridico/dist/public/assets/iara-Bd1pWhht.js
  juridico/dist/public/assets/index-28kpihTt.js
  juridico/dist/public/assets/index-B0YTb96v.js
  juridico/dist/public/assets/index-BdQq_4o_.js
  juridico/dist/public/assets/index-C024M3US.js
  juridico/dist/public/assets/index-CV6QfelB.css
  juridico/dist/public/assets/index-CyxGmtCR.js
  juridico/dist/public/assets/index-_XSsFKKV.js
  juridico/dist/public/assets/index-odkcds6s.js
  juridico/dist/public/assets/info-C5AUWl9g.js
  juridico/dist/public/assets/input-Beq58fdb.js
  juridico/dist/public/assets/juridico-pro-BWCnCh2d.js
  juridico/dist/public/assets/jurisprudencia-DvzR4k6L.js
  juridico/dist/public/assets/key-CTaoIv58.js
  juridico/dist/public/assets/label-HELNMd2g.js
  juridico/dist/public/assets/legal-assistant-7f5CZd36.js
  juridico/dist/public/assets/log-out-BeBgRdd1.js
  juridico/dist/public/assets/login-CE_5BhYm.js
  juridico/dist/public/assets/mail-BPCTbTIi.js
  juridico/dist/public/assets/message-square-BIdD7JRM.js
  juridico/dist/public/assets/not-found-GHY-j2Fl.js
  juridico/dist/public/assets/painel-processos-e5eYYiY3.js
  juridico/dist/public/assets/pdf-B75MOh95.js
  juridico/dist/public/assets/pencil-h4X763Lf.js
  juridico/dist/public/assets/pje-0rVw9OtK.js
  juridico/dist/public/assets/play-LyUojDBq.js
  juridico/dist/public/assets/playground-C0OXxrnU.js
  juridico/dist/public/assets/plus-CD9lH7pR.js
  juridico/dist/public/assets/prazos-Ca2drPlS.js
  juridico/dist/public/assets/previdenciario-CHmA8mVg.js
  juridico/dist/public/assets/refresh-cw-DLZ40eiX.js
  juridico/dist/public/assets/robo-djen-DaDoUMvg.js
  juridico/dist/public/assets/rotate-ccw-BDKSv7NN.js
  juridico/dist/public/assets/save-BtYt8O-3.js
  juridico/dist/public/assets/scale-DL44_Z-P.js
  juridico/dist/public/assets/search-CUEuJlJo.js
  juridico/dist/public/assets/select-BaIKZQjg.js
  juridico/dist/public/assets/separator-K4xwL5Pb.js
  juridico/dist/public/assets/server-YwLnhmJu.js
  juridico/dist/public/assets/settings-CdQsakcp.js
  juridico/dist/public/assets/shield-vDD54pHO.js
  juridico/dist/public/assets/slider-Dzf2vR38.js
  juridico/dist/public/assets/status--LNis53d.js
  juridico/dist/public/assets/tabs-Bxm6G3dy.js
  juridico/dist/public/assets/tag-LbJW7TIK.js
  juridico/dist/public/assets/target-BZCQz0Bh.js
  juridico/dist/public/assets/templates-juridicos-Cwfg0dU9.js
  juridico/dist/public/assets/terminal-BUZM54jF.js
  juridico/dist/public/assets/textarea-_aV9rgWP.js
  juridico/dist/public/assets/theme-toggle-BCfIU4lM.js
  juridico/dist/public/assets/tiptap-editor-BJcziLjr.js
  juridico/dist/public/assets/token-generator-ZC4hDR0T.js
  juridico/dist/public/assets/tramitacao-Mzn2xBf9.js
  juridico/dist/public/assets/trash-2-Cy2W2HFq.js
  juridico/dist/public/assets/triangle-alert-DOLme-hg.js
  juridico/dist/public/assets/upload-Mpfhr3q3.js
  juridico/dist/public/assets/useMutation-CYMlB8dT.js
  juridico/dist/public/assets/user-A83hgMSo.js
  juridico/dist/public/assets/user-check-KjU15eFV.js
  juridico/dist/public/assets/users-Do3AZQrD.js
  juridico/dist/public/assets/volume-2-Bp1t5cX0.js
  juridico/dist/public/assets/volume-x-DAyhgBMg.js
  juridico/dist/public/assets/wifi-BFhgqE2o.js
  juridico/dist/public/assets/zap-CyosTu31.js
  juridico/dist/public/favicon.svg
  juridico/dist/public/icons/icon-128x128.svg
  juridico/dist/public/icons/icon-144x144.svg
  juridico/dist/public/icons/icon-152x152.svg
  juridico/dist/public/icons/icon-192x192.svg
  juridico/dist/public/icons/icon-384x384.svg
  juridico/dist/public/icons/icon-512x512.svg
  juridico/dist/public/icons/icon-72x72.svg
  juridico/dist/public/icons/icon-96x96.svg
  juridico/dist/public/index.html
  juridico/dist/public/manifest.webmanifest
  juridico/dist/public/opengraph.jpg
  juridico/dist/public/registerSW.js
  juridico/dist/public/robots.txt
  juridico/dist/public/sw.js
  juridico/dist/public/workbox-6829fd8d.js
  juridico/index.html
  juridico/package.json
  juridico/public/favicon.svg
  juridico/public/icons/icon-128x128.svg
  juridico/public/icons/icon-144x144.svg
  juridico/public/icons/icon-152x152.svg
  juridico/public/icons/icon-192x192.svg
  juridico/public/icons/icon-384x384.svg
  juridico/public/icons/icon-512x512.svg
  juridico/public/icons/icon-72x72.svg
  juridico/public/icons/icon-96x96.svg
  juridico/public/opengraph.jpg
  juridico/public/robots.txt
  juridico/src/App.tsx
  juridico/src/components/Layout.tsx
  juridico/src/components/PinLock.tsx
  juridico/src/components/pwa-install.tsx
  juridico/src/components/theme-provider.tsx
  juridico/src/components/theme-toggle.tsx
  juridico/src/components/tiptap-editor.tsx
  juridico/src/components/ui/accordion.tsx
  juridico/src/components/ui/alert-dialog.tsx
  juridico/src/components/ui/alert.tsx
  juridico/src/components/ui/aspect-ratio.tsx
  juridico/src/components/ui/avatar.tsx
  juridico/src/components/ui/badge.tsx
  juridico/src/components/ui/breadcrumb.tsx
  juridico/src/components/ui/button-group.tsx
  juridico/src/components/ui/button.tsx
  juridico/src/components/ui/calendar.tsx
  juridico/src/components/ui/card.tsx
  juridico/src/components/ui/carousel.tsx
  juridico/src/components/ui/chart.tsx
  juridico/src/components/ui/checkbox.tsx
  juridico/src/components/ui/collapsible.tsx
  juridico/src/components/ui/command.tsx
  juridico/src/components/ui/context-menu.tsx
  juridico/src/components/ui/dialog.tsx
  juridico/src/components/ui/drawer.tsx
  juridico/src/components/ui/dropdown-menu.tsx
  juridico/src/components/ui/empty.tsx
  juridico/src/components/ui/field.tsx
  juridico/src/components/ui/form.tsx
  juridico/src/components/ui/hover-card.tsx
  juridico/src/components/ui/input-group.tsx
  juridico/src/components/ui/input-otp.tsx
  juridico/src/components/ui/input.tsx
  juridico/src/components/ui/item.tsx
  juridico/src/components/ui/kbd.tsx
  juridico/src/components/ui/label.tsx
  juridico/src/components/ui/menubar.tsx
  juridico/src/components/ui/navigation-menu.tsx
  juridico/src/components/ui/pagination.tsx
  juridico/src/components/ui/popover.tsx
  juridico/src/components/ui/progress.tsx
  juridico/src/components/ui/radio-group.tsx
  juridico/src/components/ui/resizable.tsx
  juridico/src/components/ui/scroll-area.tsx
  juridico/src/components/ui/select.tsx
  juridico/src/components/ui/separator.tsx
  juridico/src/components/ui/sheet.tsx
  juridico/src/components/ui/sidebar.tsx
  juridico/src/components/ui/skeleton.tsx
  juridico/src/components/ui/slider.tsx
  juridico/src/components/ui/sonner.tsx
  juridico/src/components/ui/spinner.tsx
  juridico/src/components/ui/switch.tsx
  juridico/src/components/ui/table.tsx
  juridico/src/components/ui/tabs.tsx
  juridico/src/components/ui/textarea.tsx
  juridico/src/components/ui/toast.tsx
  juridico/src/components/ui/toaster.tsx
  juridico/src/components/ui/toggle-group.tsx
  juridico/src/components/ui/toggle.tsx
  juridico/src/components/ui/tooltip.tsx
  juridico/src/hooks/use-mobile.tsx
  juridico/src/hooks/use-toast.ts
  juridico/src/hooks/useLocalStorage.ts
  juridico/src/index.css
  juridico/src/lib/aiDirect.ts
  juridico/src/lib/apiInterceptor.ts
  juridico/src/lib/fileExtract.ts
  juridico/src/lib/legal-formatter.ts
  juridico/src/lib/localDB.ts
  juridico/src/lib/queryClient.ts
  juridico/src/lib/speech.ts
  juridico/src/lib/storage.ts
  juridico/src/lib/sync-storage.ts
  juridico/src/lib/tts-service.ts
  juridico/src/lib/utils.ts
  juridico/src/main.tsx
  juridico/src/pages/Assistente.tsx
  juridico/src/pages/Audiencias.tsx
  juridico/src/pages/Clientes.tsx
  juridico/src/pages/ComunicacoesProcessuais.tsx
  juridico/src/pages/Configuracoes.tsx
  juridico/src/pages/Dashboard.tsx
  juridico/src/pages/Documentos.tsx
  juridico/src/pages/ExtractorJuridico.tsx
  juridico/src/pages/HtmlPlayground.tsx
  juridico/src/pages/Processos.tsx
  juridico/src/pages/Templates.tsx
  juridico/src/pages/admin.tsx
  juridico/src/pages/assinatura.tsx
  juridico/src/pages/auditoria-financeira.tsx
  juridico/src/pages/codigo.tsx
  juridico/src/pages/colaborativo.tsx
  juridico/src/pages/comparador-juridico.tsx
  juridico/src/pages/comunicacoes-cnj.tsx
  juridico/src/pages/configuracoes.tsx
  juridico/src/pages/consulta-corporativo.tsx
  juridico/src/pages/consulta-pdpj.tsx
  juridico/src/pages/consulta-processual.tsx
  juridico/src/pages/ementas.tsx
  juridico/src/pages/escritorio.tsx
  juridico/src/pages/filtrador.tsx
  juridico/src/pages/guia.tsx
  juridico/src/pages/historico.tsx
  juridico/src/pages/iara.tsx
  juridico/src/pages/juridico-pro.tsx
  juridico/src/pages/jurisprudencia.tsx
  juridico/src/pages/legal-assistant.tsx
  juridico/src/pages/login.tsx
  juridico/src/pages/not-found.tsx
  juridico/src/pages/painel-processos.tsx
  juridico/src/pages/pje.tsx
  juridico/src/pages/playground.tsx
  juridico/src/pages/prazos.tsx
  juridico/src/pages/previdenciario.tsx
  juridico/src/pages/robo-djen.tsx
  juridico/src/pages/status.tsx
  juridico/src/pages/templates-juridicos.tsx
  juridico/src/pages/token-generator.tsx
  juridico/src/pages/tramitacao.tsx
  juridico/tsconfig.json
  juridico/vite.config.ts
  sk-editor/.replit-artifact/artifact.toml
  sk-editor/SYSTEM_DOCS.md
  sk-editor/components.json
  sk-editor/dist/public/MANUAL-SK-CODE-EDITOR.md
  sk-editor/dist/public/assets/XTermConnector-udiVE6cg.js
  sk-editor/dist/public/assets/addon-fit-DX4qG4td.js
  sk-editor/dist/public/assets/addon-web-links-DIbG5aQx.js
  sk-editor/dist/public/assets/index-Cg47B_PG.css
  sk-editor/dist/public/assets/index-Dn05cZXz.js
  sk-editor/dist/public/assets/xterm-B-qIQCd3.js
  sk-editor/dist/public/favicon.svg
  sk-editor/dist/public/guia-completo-apk.md
  sk-editor/dist/public/icon-192.png
  sk-editor/dist/public/icon-512.png
  sk-editor/dist/public/index.html
  sk-editor/dist/public/manifest.json
  sk-editor/dist/public/manual-dev.md
  sk-editor/dist/public/opengraph.jpg
  sk-editor/dist/public/sw.js
  sk-editor/index.html
  sk-editor/package.json
  sk-editor/public/MANUAL-SK-CODE-EDITOR.md
  sk-editor/public/favicon.svg
  sk-editor/public/guia-completo-apk.md
  sk-editor/public/icon-192.png
  sk-editor/public/icon-512.png
  sk-editor/public/manifest.json
  sk-editor/public/manual-dev.md
  sk-editor/public/opengraph.jpg
  sk-editor/public/sw.js
  sk-editor/src/App.tsx
  sk-editor/src/components/AIChat.tsx
  sk-editor/src/components/AssistenteJuridico.tsx
  sk-editor/src/components/CampoLivre.tsx
  sk-editor/src/components/CodeEditor.tsx
  sk-editor/src/components/CombinarApps.tsx
  sk-editor/src/components/DriveBackupPanel.tsx
  sk-editor/src/components/EditorLayout.tsx
  sk-editor/src/components/FileTree.tsx
  sk-editor/src/components/GitHubPanel.tsx
  sk-editor/src/components/Manual.tsx
  sk-editor/src/components/PackageSearch.tsx
  sk-editor/src/components/Preview.tsx
  sk-editor/src/components/QuickPrompt.tsx
  sk-editor/src/components/RealTerminal.tsx
  sk-editor/src/components/SKTerminal.tsx
  sk-editor/src/components/StreamTerminal.tsx
  sk-editor/src/components/SystemStatusPanel.tsx
  sk-editor/src/components/TemplateSelector.tsx
  sk-editor/src/components/Terminal.tsx
  sk-editor/src/components/VoiceCard.tsx
  sk-editor/src/components/VoiceMode.tsx
  sk-editor/src/components/WebContainerTerminal.tsx
  sk-editor/src/components/XTermConnector.tsx
  sk-editor/src/components/ui/accordion.tsx
  sk-editor/src/components/ui/alert-dialog.tsx
  sk-editor/src/components/ui/alert.tsx
  sk-editor/src/components/ui/aspect-ratio.tsx
  sk-editor/src/components/ui/avatar.tsx
  sk-editor/src/components/ui/badge.tsx
  sk-editor/src/components/ui/breadcrumb.tsx
  sk-editor/src/components/ui/button-group.tsx
  sk-editor/src/components/ui/button.tsx
  sk-editor/src/components/ui/calendar.tsx
  sk-editor/src/components/ui/card.tsx
  sk-editor/src/components/ui/carousel.tsx
  sk-editor/src/components/ui/chart.tsx
  sk-editor/src/components/ui/checkbox.tsx
  sk-editor/src/components/ui/collapsible.tsx
  sk-editor/src/components/ui/command.tsx
  sk-editor/src/components/ui/context-menu.tsx
  sk-editor/src/components/ui/dialog.tsx
  sk-editor/src/components/ui/drawer.tsx
  sk-editor/src/components/ui/dropdown-menu.tsx
  sk-editor/src/components/ui/empty.tsx
  sk-editor/src/components/ui/field.tsx
  sk-editor/src/components/ui/form.tsx
  sk-editor/src/components/ui/hover-card.tsx
  sk-editor/src/components/ui/input-group.tsx
  sk-editor/src/components/ui/input-otp.tsx
  sk-editor/src/components/ui/input.tsx
  sk-editor/src/components/ui/item.tsx
  sk-editor/src/components/ui/kbd.tsx
  sk-editor/src/components/ui/label.tsx
  sk-editor/src/components/ui/menubar.tsx
  sk-editor/src/components/ui/navigation-menu.tsx
  sk-editor/src/components/ui/pagination.tsx
  sk-editor/src/components/ui/popover.tsx
  sk-editor/src/components/ui/progress.tsx
  sk-editor/src/components/ui/radio-group.tsx
  sk-editor/src/components/ui/resizable.tsx
  sk-editor/src/components/ui/scroll-area.tsx
  sk-editor/src/components/ui/select.tsx
  sk-editor/src/components/ui/separator.tsx
  sk-editor/src/components/ui/sheet.tsx
  sk-editor/src/components/ui/sidebar.tsx
  sk-editor/src/components/ui/skeleton.tsx
  sk-editor/src/components/ui/slider.tsx
  sk-editor/src/components/ui/sonner.tsx
  sk-editor/src/components/ui/spinner.tsx
  sk-editor/src/components/ui/switch.tsx
  sk-editor/src/components/ui/table.tsx
  sk-editor/src/components/ui/tabs.tsx
  sk-editor/src/components/ui/textarea.tsx
  sk-editor/src/components/ui/toast.tsx
  sk-editor/src/components/ui/toaster.tsx
  sk-editor/src/components/ui/toggle-group.tsx
  sk-editor/src/components/ui/toggle.tsx
  sk-editor/src/components/ui/tooltip.tsx
  sk-editor/src/hooks/use-mobile.tsx
  sk-editor/src/hooks/use-toast.ts
  sk-editor/src/index.css
  sk-editor/src/lib/ai-service.ts
  sk-editor/src/lib/github-service.ts
  sk-editor/src/lib/projects.ts
  sk-editor/src/lib/store.ts
  sk-editor/src/lib/templates.ts
  sk-editor/src/lib/tts-service.ts
  sk-editor/src/lib/utils.ts
  sk-editor/src/lib/virtual-fs.ts
  sk-editor/src/lib/zip-service.ts
  sk-editor/src/main.tsx
  sk-editor/src/pedaços de outros/ai-panel_1778769976970.tsx
  sk-editor/src/pedaços de outros/preview-panel_1778769880659.tsx
  sk-editor/src/pedaços de outros/settings_1778769824105.tsx
  sk-editor/tsconfig.json
  sk-editor/vite.config.ts
  sk-mobile/.expo/README.md
  sk-mobile/.expo/devices.json
  sk-mobile/.expo/types/router.d.ts
  sk-mobile/.expo/web/cache/production/images/android-adaptive-foreground/android-adaptive-foreground-3b544823f512e77f9b3b3b4b73f1d24f0f05d2d6111352ce92d66c01f0741b9c-cover-transparent/icon_108.png
  sk-mobile/.expo/web/cache/production/images/android-adaptive-foreground/android-adaptive-foreground-3b544823f512e77f9b3b3b4b73f1d24f0f05d2d6111352ce92d66c01f0741b9c-cover-transparent/icon_162.png
  sk-mobile/.expo/web/cache/production/images/android-adaptive-foreground/android-adaptive-foreground-3b544823f512e77f9b3b3b4b73f1d24f0f05d2d6111352ce92d66c01f0741b9c-cover-transparent/icon_216.png
  sk-mobile/.expo/web/cache/production/images/android-adaptive-foreground/android-adaptive-foreground-3b544823f512e77f9b3b3b4b73f1d24f0f05d2d6111352ce92d66c01f0741b9c-cover-transparent/icon_324.png
  sk-mobile/.expo/web/cache/production/images/android-adaptive-foreground/android-adaptive-foreground-3b544823f512e77f9b3b3b4b73f1d24f0f05d2d6111352ce92d66c01f0741b9c-cover-transparent/icon_432.png
  sk-mobile/.expo/web/cache/production/images/android-standard-square/android-standard-square-3b544823f512e77f9b3b3b4b73f1d24f0f05d2d6111352ce92d66c01f0741b9c-cover-transparent/icon_144.png
  sk-mobile/.expo/web/cache/production/images/android-standard-square/android-standard-square-3b544823f512e77f9b3b3b4b73f1d24f0f05d2d6111352ce92d66c01f0741b9c-cover-transparent/icon_192.png
  sk-mobile/.expo/web/cache/production/images/android-standard-square/android-standard-square-3b544823f512e77f9b3b3b4b73f1d24f0f05d2d6111352ce92d66c01f0741b9c-cover-transparent/icon_48.png
  sk-mobile/.expo/web/cache/production/images/android-standard-square/android-standard-square-3b544823f512e77f9b3b3b4b73f1d24f0f05d2d6111352ce92d66c01f0741b9c-cover-transparent/icon_72.png
  sk-mobile/.expo/web/cache/production/images/android-standard-square/android-standard-square-3b544823f512e77f9b3b3b4b73f1d24f0f05d2d6111352ce92d66c01f0741b9c-cover-transparent/icon_96.png
  sk-mobile/.expo/web/cache/production/images/favicon/favicon-3b544823f512e77f9b3b3b4b73f1d24f0f05d2d6111352ce92d66c01f0741b9c-contain-transparent/favicon-48.png
  sk-mobile/.expo/web/cache/production/images/splash-android/splash-android-3b544823f512e77f9b3b3b4b73f1d24f0f05d2d6111352ce92d66c01f0741b9c-contain/icon_200.png
  sk-mobile/.expo/web/cache/production/images/splash-android/splash-android-3b544823f512e77f9b3b3b4b73f1d24f0f05d2d6111352ce92d66c01f0741b9c-contain/icon_300.png
  sk-mobile/.expo/web/cache/production/images/splash-android/splash-android-3b544823f512e77f9b3b3b4b73f1d24f0f05d2d6111352ce92d66c01f0741b9c-contain/icon_400.png
  sk-mobile/.expo/web/cache/production/images/splash-android/splash-android-3b544823f512e77f9b3b3b4b73f1d24f0f05d2d6111352ce92d66c01f0741b9c-contain/icon_600.png
  sk-mobile/.expo/web/cache/production/images/splash-android/splash-android-3b544823f512e77f9b3b3b4b73f1d24f0f05d2d6111352ce92d66c01f0741b9c-contain/icon_800.png
  sk-mobile/.gitignore
  sk-mobile/.replit-artifact/artifact.toml
  sk-mobile/android/.gitignore
  sk-mobile/android/.gradle/8.14.3/checksums/checksums.lock
  sk-mobile/android/.gradle/8.14.3/checksums/md5-checksums.bin
  sk-mobile/android/.gradle/8.14.3/checksums/sha1-checksums.bin
  sk-mobile/android/.gradle/8.14.3/fileHashes/fileHashes.lock
  sk-mobile/android/.gradle/buildOutputCleanup/buildOutputCleanup.lock
  sk-mobile/android/.gradle/buildOutputCleanup/cache.properties
  sk-mobile/android/app/build.gradle
  sk-mobile/android/app/debug.keystore
  sk-mobile/android/app/proguard-rules.pro
  sk-mobile/android/app/src/debug/AndroidManifest.xml
  sk-mobile/android/app/src/debugOptimized/AndroidManifest.xml
  sk-mobile/android/app/src/main/AndroidManifest.xml
  sk-mobile/android/app/src/main/java/com/anonymous/skmobile/MainActivity.kt
  sk-mobile/android/app/src/main/java/com/anonymous/skmobile/MainApplication.kt
  sk-mobile/android/app/src/main/res/drawable-hdpi/splashscreen_logo.png
  sk-mobile/android/app/src/main/res/drawable-mdpi/splashscreen_logo.png
  sk-mobile/android/app/src/main/res/drawable-xhdpi/splashscreen_logo.png
  sk-mobile/android/app/src/main/res/drawable-xxhdpi/splashscreen_logo.png
  sk-mobile/android/app/src/main/res/drawable-xxxhdpi/splashscreen_logo.png
  sk-mobile/android/app/src/main/res/drawable/ic_launcher_background.xml
  sk-mobile/android/app/src/main/res/drawable/rn_edit_text_material.xml
  sk-mobile/android/app/src/main/res/mipmap-hdpi/ic_launcher.webp
  sk-mobile/android/app/src/main/res/mipmap-hdpi/ic_launcher_foreground.webp
  sk-mobile/android/app/src/main/res/mipmap-mdpi/ic_launcher.webp
  sk-mobile/android/app/src/main/res/mipmap-mdpi/ic_launcher_foreground.webp
  sk-mobile/android/app/src/main/res/mipmap-xhdpi/ic_launcher.webp
  sk-mobile/android/app/src/main/res/mipmap-xhdpi/ic_launcher_foreground.webp
  sk-mobile/android/app/src/main/res/mipmap-xxhdpi/ic_launcher.webp
  sk-mobile/android/app/src/main/res/mipmap-xxhdpi/ic_launcher_foreground.webp
  sk-mobile/android/app/src/main/res/mipmap-xxxhdpi/ic_launcher.webp
  sk-mobile/android/app/src/main/res/mipmap-xxxhdpi/ic_launcher_foreground.webp
  sk-mobile/android/app/src/main/res/values-night/colors.xml
  sk-mobile/android/app/src/main/res/values/colors.xml
  sk-mobile/android/app/src/main/res/values/strings.xml
  sk-mobile/android/app/src/main/res/values/styles.xml
  sk-mobile/android/build.gradle
  sk-mobile/android/gradle.properties
  sk-mobile/android/gradle/wrapper/gradle-wrapper.jar
  sk-mobile/android/gradle/wrapper/gradle-wrapper.properties
  sk-mobile/android/gradlew
  sk-mobile/android/gradlew.bat
  sk-mobile/android/settings.gradle
  sk-mobile/app.json
  sk-mobile/app/(tabs)/_layout.tsx
  sk-mobile/app/(tabs)/clientes.tsx
  sk-mobile/app/(tabs)/configuracoes.tsx
  sk-mobile/app/(tabs)/iara.tsx
  sk-mobile/app/(tabs)/index.tsx
  sk-mobile/app/(tabs)/juridico.tsx
  sk-mobile/app/(tabs)/processos.tsx
  sk-mobile/app/+not-found.tsx
  sk-mobile/app/_layout.tsx
  sk-mobile/assets/images/icon.png
  sk-mobile/babel.config.js
  sk-mobile/components/ErrorBoundary.tsx
  sk-mobile/components/ErrorFallback.tsx
  sk-mobile/components/KeyboardAwareScrollViewCompat.tsx
  sk-mobile/constants/colors.ts
  sk-mobile/eas.json
  sk-mobile/expo-env.d.ts
  sk-mobile/hooks/useColors.ts
  sk-mobile/metro.config.js
  sk-mobile/package.json
  sk-mobile/scripts/build.js
  sk-mobile/server/serve.js
  sk-mobile/server/templates/landing-page.html
  sk-mobile/tsconfig.json
```

---

*Plano gerado pelo SK Code Editor — 01/10/2026, 06:58:06*