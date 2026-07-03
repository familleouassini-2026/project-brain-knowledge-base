# How to Work with AI on Project Brain

**Document ID**: AI-002  
**Version**: 1.0.0  
**Status**: Draft  
**Owner**: Project Brain  
**Last Update**: 2026-07-03

## Purpose

This document explains how AI assistants should be used without becoming the unstable memory of the project.

## Rules

## 1. The repository is the memory

AI conversations are useful for reasoning, but they are not the source of truth.

Important decisions must be transferred to the knowledge base.

## 2. Start each session with context

The AI should receive:

- `AI/CURRENT_CONTEXT.md`
- the specific documents related to the current task;
- the current objective.

## 3. AI must not decide alone

The AI can propose, analyse and draft.

The Product Owner validates.

## 4. AI must be judged by deliverables

Long reasoning is not enough.

A useful AI session should end with a concrete output:

- document;
- release;
- code;
- analysis;
- test;
- roadmap update.

## 5. AI must respect the roadmap

The AI must not introduce new concepts that are not necessary for the current release.

If a new idea appears, it should be placed in the backlog unless it solves a current problem.

## 6. AI must explain technical consequences

The Product Owner should not need to know the whole architecture.

The AI must translate business needs into understandable impacts and options.
